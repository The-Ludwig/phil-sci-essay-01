LaTeX-template
===
[Latest PDF Version](https://github.com/The-Ludwig/latex-template/releases/latest/download/latex-template.pdf)
[![Build LaTeX](https://github.com/The-Ludwig/latex-template/actions/workflows/build.yml/badge.svg)](https://github.com/The-Ludwig/latex-template/actions/workflows/build.yml)

Template for a reproducable LaTeX workflow using texlive, latexmk, make and automated builds.

**Remember to replace the paths in this README.md file, so you use your own batches**

This can be either used for normal documents or for beamer slides.
Please look into the comments of `main.tex` to see how to setup beamer. 

# Building
To produce the output to `build/main.pdf` simply run
```sh
make
```

To use continuous building (i.e. while working on the document) use 
```sh
make work
```

# Dependencies 
You need 
- texlive 
- make

# Credits
As with all of my LaTeX stuff: Since I learned it thanks to the [PeP Toolbox Workshop](https://toolbox.pep-dortmund.org/)
you will proably find a lot of copied code from their workshop. If you want to learn LaTeX and speak German, have a look at their awesome resources! :)
