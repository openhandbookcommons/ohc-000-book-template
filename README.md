# Open Handbook Commons — Quarto Book Template

This repository is a starter template for creating print-friendly, community-written PDF books
for the Open Handbook Commons Project.

## What this template produces

- A print-ready PDF (A4, spiral-binding optimized margins)
- A simple, consistent front matter (mission, license, disclaimers, printing tips)
- A clean chapter structure for community contributions

## Build

### Prerequisites
- [Quarto](https://quarto.org/)
- A LaTeX distribution:
  - TinyTex: `quarto install tinytex`
- Python packages: 
  - `pip install pyyaml pypdf reportlab`

### Render PDF
```bash
quarto render
```

Output will appear in `_book/`.


