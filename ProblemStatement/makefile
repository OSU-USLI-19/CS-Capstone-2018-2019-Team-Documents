# LaTeX Makefile, THIS ONLY WORKS TO PDF!!! So my figures work :)
FILE=$(shell egrep -l '^[^%]*\\begin\{document\}' *.tex)

pdf: $(FILE)
	pdflatex -shell-escape $(FILE)

all: pdf

clean:
	rm -f *.pdf *.ps *.dvi *.out *.log *.aux *.bbl *.blg *.pyg

.PHONY: clean
