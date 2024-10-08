# Master Thesis

This repository contains the LaTeX source files and associated materials for my master thesis as an Aerospace Engineering student at the University of Padua (UniPD). 

## Compile into PDF

![GitHub release (latest by date)](https://img.shields.io/github/v/release/mattiagre/master-thesis)
[![Compile LaTeX](https://github.com/mattiagre/master-thesis/actions/workflows/compile-latex.yml/badge.svg)](https://github.com/mattiagre/master-thesis/actions/workflows/compile-latex.yml)

Compile LaTeX locally running `pdflatex -halt-on-error -interaction=nonstopmode -shell-escape Gregnanin_Mattia.tex`. 

To produce a valid PDF/A-3b compliant PDF, run the following Ghostscript script inside `pdfa` folder: `gs -dBATCH -dNOPAUSE -dNOSAFER -sDEVICE=pdfwrite -dPDFA=3 -dPDFACompatibilityPolicy=2 -sColorConversionStrategy=RGB -o Gregnanin_Mattia.pdf <PATH>/pdfa/PDFA_def.ps ../Gregnanin_Mattia.pdf`.


## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).