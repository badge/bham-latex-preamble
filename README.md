bham-latex-preamble
===================

This project holds the LaTeX preamble file of my PhD thesis, for submission at the University of Birmingham. It is a work in progress, but is largely complete. Its features include:

* The Linux Libertine font, in place of Computer Modern, to make things look nicer
* Old-style (aka text) figures for more readable numbers
* Sans-serif font (currently Helvetica Neue) for headings
* New theorem styles, example and algorithm, for mathematical examples and computer algorithms respectively
* Separate PDF and Print versions of your document; the PDF version will have equal borders and coloured links for references, citations and external links
* Packages for beautifying tables

----

**Warning!**

preamble.tex uses the fontspec package that is not supported by vanilla LaTeX. To typeset using this package enabled, LuaLaTeX or XeLaTeX is required.

----

**Downloading**

Click on the Downloads tab to the top-right of this page, then click *Download as zip* or *Download as tar.gz*. This gives you the preamble.tex file, along with the examples files and this readme.

----

**Usage**

To import the preamble.tex file, use

    \input{preamble.tex}

after the document class. Immediately before that line, include the line

    \newcommand{\ispdfversion}{true}

This line tells the file whether you want the PDF or print version. If changing this (the other option is 'false'), be sure to trash all auxillary (.aux, .synctex, etc.) files before rebuilding the file.

----

**Future Plans**

I'm currently in the process of packaging things up into a class file, to make life easier and more consistent.