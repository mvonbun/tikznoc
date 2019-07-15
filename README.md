# tikznoc
A package for LaTeX PGF/TikZ to draw Network-on-Chip (NoC) schematics

## Installation

From the repo's root directory, call `latex tikznoc.ins` and copy the generated
`tikznoc.sty` to a location where LaTeX can find it.

For local / single projects only, this would be your main file's folder.

Otherwise, copy it to your texmf tree, e.g. for the user this would be
`~/texmf/tex/latex/tikznoc`.


## Documenation

From the repo's root directory, call `latex tikznoc.ins && pdflatex tikznoc.dtx
&& makeindex -s gglo.ist -o tikznoc.gls tikznoc.glo && makeindex -s gind.ist -o
tikznoc.ind tikznoc.idx && pdflatex tikznoc.dtx` to generate the package
documentation with examples.


