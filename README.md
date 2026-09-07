# WorkshopReport
A repository to coordinate writing a workshop report document on the 2026 Polyhedra In Lean workshop.

## Usage
You need to install the [`JuliaMono`](https://juliamono.netlify.app/download/) font for proper unicode support, which we want for the code listings. You also need to build with `xelatex` instead of `pdflatex` to use it.

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

Add your content to a new file called `my_group_report.tex` and include it in the `main.tex` file. You can find an example in `stub_section.tex`. Don't forget to add your name to the `authors.tex` file.
