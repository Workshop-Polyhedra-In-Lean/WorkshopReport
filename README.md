# WorkshopReport
A repository to coordinate writing a workshop report document on the 2026 Polyhedra In Lean workshop.

## Usage
You need to install the [`JuliaMono`](https://juliamono.netlify.app/download/) font for proper unicode support, which we want for the code listings. You also need to build with `xelatex` instead of `pdflatex` to use it. If you don't want to install the font, comment the `\setmonofont{JuliaMono}` in `main.tex` and prepare for latex warnings and placeholder characters in the compiled document.

To build, say
```
  xelatex main
```
If you change the `references.bib` file, run
```
  bibtex main
  xelatex main
  xelatex main
```
to build the bibliography.

Don't forget to add your name to the `authors.tex` file.
