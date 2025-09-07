# Project Documentation

This directory contains the LaTeX source files for the project documentation.

## Files

- `documentation.tex`: Main LaTeX source file for the documentation.
- `Makefile`: Makefile to build the PDF documentation easily.

## Prerequisites

- A LaTeX distribution installed on your system (e.g., TeX Live, MacTeX, BasicTeX).
- `pdflatex` command available in your PATH.

## Building the Documentation

To compile the documentation PDF, run:

```bash
make
```

This will generate `documentation.pdf` in the current directory.

## Viewing the PDF

To compile and open the PDF (macOS only), run:

```bash
make view
```

## Cleaning Up

To remove all generated files, run:

```bash
make clean
```

## Auto Compiling

To make auto compiling, run:

```bash
make auto
```

## Installing LaTeX Dependencies (macOS)

If you do not have LaTeX installed, you can install BasicTeX using Homebrew:

```bash
make install-deps
```

After installation, update the TeX Live manager and install recommended packages:

```bash
sudo tlmgr update --self
sudo tlmgr install collection-latexrecommended
```

## Editing the Documentation

Edit the `documentation.tex` file to add or modify the documentation content. Use any LaTeX editor or a plain text editor.

## Additional Resources

- [LaTeX Project](https://www.latex-project.org/)
- [Overleaf Online Editor](https://www.overleaf.com/)
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)

## Extension Used For Latex

- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [LaTeX Snippets](https://marketplace.visualstudio.com/items?itemName=JeffersonQin.latex-snippets-jeff)
- [LaTeX](https://marketplace.visualstudio.com/items?itemName=mathematic.vscode-latex)
- [LaTeX Utilities](https://marketplace.visualstudio.com/items?itemName=tecosaur.latex-utilities)