# CV - Thomas Bermúdez Mora

Professional curriculum vitae built with LaTeX for a clean, consistent, and easily maintainable resume format.

## 📄 Overview

This repository contains my professional CV in LaTeX format, designed with a focus on readability and ATS (Applicant Tracking System) compatibility.

## 🎨 Template

Based on the **CV - Harvard-like** template:

| | |
|---|---|
| **Author** | Aline R. Antunes |
| **License** | LaTeX Project Public License 1.3c |
| **Style** | Harvard CV format |

## 🛠️ Requirements

To compile this CV, you need a LaTeX distribution installed:

- **Windows:** [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/)
- **macOS:** [MacTeX](https://tug.org/mactex/)
- **Linux:** TeX Live (`sudo apt install texlive-full`)

### Required LaTeX Packages

The following packages are used (typically included in full LaTeX distributions):

- `graphicx` - Graphics support
- `hyperref` - Hyperlinks
- `enumitem` - List customization
- `inputenc` - UTF-8 encoding
- `fontenc` - Font encoding
- `babel` - Language support
- `geometry` - Page margins
- `lipsum` - Placeholder text (optional)

## 🚀 Compilation

### Using pdflatex (Command Line)

```bash
pdflatex "CV - Thomas Bermúdez Mora.tex"
```

### Using latexmk (Recommended)

```bash
latexmk -pdf "CV - Thomas Bermúdez Mora.tex"
```

### Using VS Code with LaTeX Workshop

1. Install the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension
2. Open the `.tex` file
3. Press `Ctrl+Alt+B` (or `Cmd+Alt+B` on macOS) to build

## 📁 Project Structure

```
cv-latex/
├── CV - Thomas Bermúdez Mora.tex    # Main LaTeX source file
├── CV - Thomas Bermúdez Mora.pdf    # Compiled PDF output
├── README.md                         # This file
└── [auxiliary files]                 # Generated during compilation
    ├── *.aux
    ├── *.log
    ├── *.out
    └── *.synctex.gz
```

## ✏️ Customization

To customize this CV for your own use:

1. **Personal Information:** Update the header section with your name, email, phone, LinkedIn, and website
2. **Profile:** Modify the profile summary to reflect your expertise
3. **Experience:** Add/edit work experience entries in the `\begin{itemize}` blocks
4. **Education:** Update educational background
5. **Skills:** Modify technical and soft skills sections
6. **Extracurricular Activities:** Add volunteer work or side projects

## 📐 Layout Settings

Current page geometry:
- **Margins:** Left/Right: 1.06cm, Top: 1.7cm, Bottom: 0.49cm
- **Font size:** 11pt
- **Paper size:** Default (Letter/A4)

To adjust margins, modify the `geometry` package options in the preamble.

## 🧹 Cleaning Auxiliary Files

To remove generated auxiliary files:

```bash
# Windows (PowerShell)
Remove-Item "CV - Thomas Bermúdez Mora.aux", "CV - Thomas Bermúdez Mora.log", "CV - Thomas Bermúdez Mora.out", "CV - Thomas Bermúdez Mora.fls", "CV - Thomas Bermúdez Mora.fdb_latexmk", "CV - Thomas Bermúdez Mora.synctex.gz"

# Linux/macOS
rm -f *.aux *.log *.out *.fls *.fdb_latexmk *.synctex.gz
```

Or using latexmk:

```bash
latexmk -c
```

## 📝 License

This CV is based on the **CV - Harvard-like** template by [Aline R. Antunes](https://www.overleaf.com/latex/templates/cv-harvard-like/gcfcvhkpkshx), licensed under the [LaTeX Project Public License 1.3c](https://www.latex-project.org/lppl/lppl-1-3c/).

---

**Author:** Thomas Emanuel Bermúdez Mora  
**Contact:** [bmthomas.code@gmail.com](mailto:bmthomas.code@gmail.com)  
**Website:** [thomasbm.com](https://thomasbm.com)
