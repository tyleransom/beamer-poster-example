This repository contains files of an example beamer poster. The main file to compile the PDF output is the `.tex` file, which calls the `.sty` file.

## Configuring the poster
The structure of the poster (i.e. how large the title box is, the overall color scheme, etc.) is all controlled in the file `beamerposterexample.sty`.

Control over the contents of the poster proceeds as one would in beamer. The main difference is that now the poster is one "slide," meaning that the user should specify multiple columns. I divided up the poster into two slides stacked on top of each other using the "part" environment. I this sense, the poster is composed of two "half-slides," each with three columns.

## Colors
As hinted to previously, the color scheme can be changed in the first section of `beamerposterexample.sty`. You can create your own colors that exactly match those of your institution using RGB codes and the `xcolor` package in LaTeX.

## Disclaimer
I am not allowed to share the images included in the top-left and top-right corners of the poster, as these are protected by copyright. You should replace these with official images from your institution.

## Questions?
If you have questions or encounter problems, feel free to contact me via the repository's issue tracker.
