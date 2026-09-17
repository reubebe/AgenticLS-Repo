# OpenTrial AgenticLS manuscript

This package contains the double-blind, four-page short-paper manuscript prepared for the NeurIPS 2026 workshop **Agentic AI for Biological Discovery**.

## Files

- `paper.tex`: manuscript source
- `references.bib`: bibliography
- `neurips_2026.sty`: NeurIPS 2026 style file
- `OpenTrial_AgenticLS_2026.pdf`: compiled review PDF

## Build

Run:

```bash
pdflatex paper
bibtex paper
pdflatex paper
pdflatex paper
```

The references begin on page 5, so the main paper occupies four pages. The review version is anonymous and does not include the public repository URL. Restore author details and the repository link only for a non-anonymous version or when the venue's policy permits it.

