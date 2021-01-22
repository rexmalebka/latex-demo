# latex-demo
demo of latex

## requirements

- pdflatex
- chktex

## structure

```bash
.
├── README.md
├── automation
├── entrypoint.pdf
├── out
└── src
    ├── bib
    ├── entrypoint.tex
    ├── images
    └── sections
        ├── sec1.tex
        ├── sec2.tex
        └── sec3.tex
```

- `automation` bash script with latex functions
- `entrypoint.pdf` pdf output file 
- `out/` out directory for intermediate files
- `src/` source files for latex
- `src/entrypoint.tex` entrypoint file
- `src/images/` images directory  
- `src/sections` sections of latex files
- `src/bib/` bib files directory

## how to

1.- clone this repo
> git clone https://github.com/rexmalebka/latex-demo.git

2.- source automation scripts
> source automation

3.- build intermediate files
> build

4.- Lint to check errors on latex 
> lint

5.- convert to pdf
> create

6.- clean files
> clean

