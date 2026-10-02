# OpenTrial AgenticLS manuscript

This package contains the camera-ready, four-page short-paper manuscript accepted as a poster at the NeurIPS 2026 workshop **Agentic AI for Biological Discovery**.

## Files

- `paper.tex`: manuscript source
- `references.bib`: bibliography
- `neurips_2026.sty`: NeurIPS 2026 style file
- `OpenTrial_AgenticLS_2026.pdf`: compiled camera-ready PDF

## Build

Run:

```bash
pdflatex paper
bibtex paper
pdflatex paper
pdflatex paper
```

The references begin on page 5, so the main paper occupies four pages. The camera-ready version uses the `final` style option and lists the authors: Reuben N Addison, PhD (DePauw University) and Shucheng Cao (McGill University). Remove `final` from the `\usepackage` line to rebuild the anonymous review version.

