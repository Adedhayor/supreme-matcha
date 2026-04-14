# CMYK Color Reference — #IkeMide26

These designs are provided in RGB hex. For print production, convert to CMYK.

| Color Name     | Hex (RGB) | Approximate CMYK       | Pantone Match (approx) |
|----------------|-----------|------------------------|------------------------|
| Matcha Deep    | #4A6741   | C:55 M:20 Y:65 K:30   | Pantone 7743 C         |
| Matcha Mid     | #7BA05B   | C:45 M:10 Y:65 K:5    | Pantone 7489 C         |
| Matcha Light   | #B6D89C   | C:28 M:0  Y:40 K:0    | Pantone 7487 C         |
| Matcha Pale    | #E2F0D6   | C:12 M:0  Y:18 K:0    | Pantone 9561 C         |
| Blush Mid      | #E8A0B4   | C:5  M:40 Y:10 K:0    | Pantone 7430 C         |
| Blush Deep     | #C27A8E   | C:10 M:52 Y:20 K:5    | Pantone 7432 C         |
| Blush Light    | #F5CDD8   | C:2  M:22 Y:6  K:0    | Pantone 9340 C         |
| Cream          | #FDF8F0   | C:0  M:2  Y:6  K:1    | Pantone 9142 C         |
| Latte          | #D4C5A9   | C:12 M:14 Y:28 K:5    | Pantone 9185 C         |
| Espresso       | #3D2B1F   | C:40 M:55 Y:60 K:70   | Pantone Black 4 C      |
| Gold Leaf      | #C9A84C   | C:15 M:25 Y:75 K:5    | Pantone 7753 C         |
| Honey          | #E8C547   | C:8  M:18 Y:78 K:0    | Pantone 7549 C         |

---

## Print Method Recommendations

### DTG (Direct to Garment)
- **Best for**: Concepts A and D — handles gradients, multi-color illustrations, and the matcha cup latte-art gradient
- **Color count**: Unlimited
- **Garment color note**: DTG prints best on white or light-colored garments. For Midnight Matcha (dark espresso garment), request a white underbase layer before printing.

### Screen Printing
- **Best for**: Concepts B and C — minimal color count, high contrast, crisp edges
- **Recommended max colors**: 4 per design to keep cost manageable
- **Recommended spot color build for Concept B (3 colors)**:
  - Spot 1: Matcha Deep (#4A6741 → Pantone 7743 C)
  - Spot 2: Blush Mid (#E8A0B4 → Pantone 7430 C)
  - Spot 3: Gold Leaf (#C9A84C → Pantone 7753 C)

### Heat Transfer Vinyl (HTV)
- **Best for**: Concept C (Minimal Mark) and Concept B (typographic, high contrast)
- **Limitation**: Gradients not supported — flatten matcha cup gradient to solid fills before sending to HTV production

---

## Critical Color Notes

> **Greens will shift in CMYK conversion.** Matcha greens (#4A6741, #7BA05B) are in the yellow-green range and may appear more yellow or less saturated when converted to CMYK process printing. Always request a **proof print** before full production run.

> **Pantone matching is strongly recommended** for Matcha Deep and Matcha Mid to ensure color consistency across the full event. A garment-printed with process CMYK that varies 10% from design intent will be noticeable when all garments are worn together in group photos.

> **Gold Leaf (#C9A84C)** will lose some of its metallic warmth in standard CMYK. For a premium metallic gold effect, request **foil printing** or **metallic screen ink** as an additional specialty layer on the BRIDE ♡ variants.

---

## File Naming Convention

```
ikemide26-[concept]-[colorway]-[role].svg

concept   : a | b | b2 | c | d
colorway  : matcha-classic | sage-rose | pink-cloud | midnight-matcha
role      : (none) | bride | squad
```

### Example filenames
- `ikemide26-a-matcha-classic.svg` — Concept A, Matcha Classic colorway, standard
- `ikemide26-b-midnight-matcha-bride.svg` — Concept B, dark garment, BRIDE variant
- `ikemide26-c-pink-cloud-squad.svg` — Concept C, Pink Cloud, MATCHA SQUAD variant

---

## Pre-Press Checklist

Before sending any file to the printer:

- [ ] SVG `viewBox` is `0 0 3000 3000` (10" × 10" at 300 dpi)
- [ ] All colors converted from CSS variables to hardcoded hex in the SVG `<style>` block or inline attributes
- [ ] No raster/bitmap images embedded — 100% vector paths
- [ ] Font: either embedded via `@import` in SVG `<style>`, or convert text to outlines (`<path>`)
- [ ] Background: transparent (no white `<rect>` behind design)
- [ ] Minimum 200px margin from canvas edges on all sides
- [ ] Convert final "best" versions to path outlines for maximum compatibility
- [ ] Provide CMYK conversion reference (this file) to printer
- [ ] Request a proof print before full production run
- [ ] For dark garments (Midnight Matcha): confirm underbase white layer with printer

---

*#IkeMide26 — Pre-Wedding Slumber Party Merchandise*
*Design System generated April 2026*
