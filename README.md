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
- `src/sections/` sections of latex files must be consecutive `src/sections/sec1.tex, src/sections/sec2.tex, src/sections/sec3.tex, ..., src/sections/secn.tex`
- `src/bib/` bib files directory 

## colaboration

1. create a pull request in the format `usename/change`
2. wait for linting checks, if fails, check the logs in `actions` sections
3. merge the changes 
4. commit the automation PR for rendering the final pdf, if fails, check the logs in `actions` section 

## how to run it locally

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

