# Thesis template
A template for a master thesis at UniMORE.  
## Compilation command
(In Texmaker)
```bash
pdflatex -synctex=1 -interaction=nonstopmode %.tex|makeglossaries %|bibtex %.aux|pdflatex -synctex=1 -interaction=nonstopmode %.tex|pdflatex -synctex=1 -interaction=nonstopmode %.tex|xdg-open %.pdf
```
## Important reminder
You are forbidden from using the University's logo.  
## A preview?
You can see the PDF in github releases.  
