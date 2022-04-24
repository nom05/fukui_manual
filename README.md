# Manual of Fukui v220331
This is the current manual of the Fukui v220331, a program developed as a multipurpose tool to perform chemical reactivity indices called ``Fukui indices'', \(\sigma\)/\(\pi\) separation of atomic populations (reading a input file with the molecular orbital symmetry) and the calculation of atomic overlap matrices as a previous step to compute the $N$-electron delocalization indices (employed for aromaticity studies, for example) and condensed 2-center Fukui indices, used for studies of reactivity and resonance effects. The program reads points grids from several sources and, therefore, it is independent of the type of real-space atomic electron density partitioning employed

## Author and collaborators
  - Nicolás Otero Martínez - nom05 (at) uvigo.es - University of Vigo

## MIT license
See corresponding file called [`LICENSE`](LICENSE) for more details.

## Compile the code
After cloning the repository, enter in the new directory, go to `figures` and compile the simplified flowchart (it is a figure necessary in the main LaTeX code of the manual:
```
pdflatex flowchart.tex
```
After the successful compilation go back to the main directory and compile the code:
```
pdflatex manual-fukui-220402-memoir.tex
pdflatex manual-fukui-220402-memoir.tex
biber manual-fukui-220402-memoir
pdflatex manual-fukui-220402-memoir.tex
pdflatex manual-fukui-220402-memoir.tex
```
