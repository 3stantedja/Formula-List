# Formula List
## What is this?
This was an attempt to replicate Cambridge Assessment's *List of Formulae and Tables of the Normal Distribution* using LaTeX. It served as a place for me to practice LaTeX, so be wary of how I wrote the document.

## Why do you make this?
Usually boils down to the following reasons:
1. Make my own notes/list of formulae
2. As an excuse to practice using LaTeX

## Plans for the future
In the future I wanted to make it so it's more than just a list of formulae. Hopefully it'll contain more documentation such as how to use it, what behaviour it exhibits, if cases (ex. what happens when **sin² _x_** is differentiated). The approach that I want to take is more like `man` entries, but shorter.

I did mention that it'll be (somewhat) short because it is designed to be used as a material for revising. With that, I don't need to write as much as a Wikipedia entry, while keeping relevant information easily available to be printed on. This means that it will assume that you have some prior knowledge of a subject matter (for instance trigonometry).

Currently, I'm basing this off Cambridge Assessment's curriculum because I've been in that curriculum for 4 years (so both IGCSE and A Levels), and its main inspiriation is the aformentioned List of Formulae. As time goes on hopefully this will be more relevant to other curricula and even university.

## How do I contribute?
You'll need at least a working TeX installation.

The packages needed to build the document are:
* latex
* subfiles
* amsmath
* inputenc
* anysize
* mathtools
* mathpazo
* mathptmx

Then clone the repo to your working directory.

To build in terminal (assuming you're in the project directory),
```bash
latexmk Formula\ sheet.tex
```
or
```bash
pdflatex Formula\ sheet.tex
```
I'd recommend using Atom (with a number of packages) to edit.


[1]: https://www.latex-project.org/get/
