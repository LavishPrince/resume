# Resume

This repository contains my resume, written in LaTeX.

## Compiling the Resume

The resume can be compiled using a standard LaTeX distribution. A GitHub Actions workflow (`.github/workflows/compile-resume.yaml`) is also set up to automatically compile the `resume.tex` file into a PDF.

To compile locally, ensure you have a LaTeX distribution (e.g., TeX Live, MiKTeX) installed and run:

```bash
pdflatex resume.tex
```

This will generate `resume.pdf` in the same directory.

## Viewing the Resume

Once compiled, the `resume.pdf` file can be viewed with any PDF reader.