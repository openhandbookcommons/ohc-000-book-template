# Open Handbook Commons — Quarto Book Template

This repository is a **starter template** for creating print-friendly, community-written PDF books
for the **Open Handbook Commons Project**.

## What this template produces

- A **print-ready PDF** (A4, spiral-binding optimized margins)
- A simple, consistent **front matter** (mission, license, printing tips)
- A clean chapter structure for community contributions

## Build

### Prerequisites
- [Quarto](https://quarto.org/)
- A LaTeX distribution:
  - TinyTex: `quarto install tinytex`

### Render PDF
```bash
quarto render
```

Output will appear in `_book/`.

## Project defaults (print-first)

- Paper: **A4**
- Margins: **left=30mm** (binding), **right=20mm**, **top=20mm**, **bottom=25mm**
- Font size: **11pt**
- Line spacing: **1.35**

## Licensing

Unless otherwise stated, all content in this repository is licensed under:
**CC BY-NC-SA 4.0** (Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International).
See `LICENSE.md`.

## Contributing

Please see `CONTRIBUTING.md` and `AI_POLICY.md`.

