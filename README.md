# LaTeX Template

Open this folder in VS Code and edit `main.tex`.

This workspace is configured for side-by-side editing:

- `main.tex` stays in the left editor.
- The PDF preview opens in the right editor group.
- VS Code auto-saves after a short delay, which triggers an automatic rebuild.
- The PDF refreshes after each rebuild.

Setup in this folder:

- Build engine: `latexmk` with TeX Live
- VS Code extension: `James-Yu.latex-workshop`
- PDF viewer: built-in tab viewer on the right

How to use it:

- Open `main.tex`.
- Run `LaTeX Workshop: View LaTeX PDF file side by side` once.
- Start typing. After the auto-save delay, the PDF rebuilds and refreshes.

Manual build options:

- Save `main.tex` to trigger LaTeX Workshop auto-build.
- Or run `LaTeX Workshop: Build LaTeX project`.
- Or run `latexmk -pdf main.tex` in the terminal.

The generated PDF and auxiliary files are written next to `main.tex`.
The machine now has `latex`, `pdflatex`, and `latexmk` installed through Homebrew `texlive`.
Use `pdflatex` or `latexmk -pdf` when you want a PDF. Plain `latex` normally produces DVI output rather than a PDF.
