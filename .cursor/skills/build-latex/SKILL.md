---
name: build-latex
description: Build LaTeX project using latexmk with XeLaTeX engine. Use when the user asks to compile, build, or render the LaTeX document, or mentions latexmk, xelatex, PDF generation, or compilation errors.
---

# Build LaTeX

## Build Command

```bash
latexmk -xelatex -f -interaction=nonstopmode main.tex
```