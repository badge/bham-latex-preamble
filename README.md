bham-latex-preamble
===================

This project holds the LaTeX preamble file of my PhD thesis, for submission at the University of Birmingham. It is a work in progress, but is largely complete. Its features include:

* The Linux Libertine font, in place of Computer Modern, to make things look nicer
* Old-style (aka text) figures) for more readable numbers
* Sans-serif font (currently Helvetica Neue) for headings
* New theorem styles, example and algorithm, for mathematical examples and computer algorithms respectively
* Separate PDF and Print versions of your document; the PDF version will have equal borders and coloured links for references, citations and external links
* Packages for beautifying tables

----

**Warning!**

preamble.tex uses the fontspec package that is not supported by vanilla LaTeX. To typeset using this package enabled, LuaLaTeX or XeLaTeX is required.