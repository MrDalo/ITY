#
# Projetk: proj4.tex
# Author: Dalibor Kralik
#

project = proj4
all: proj4


proj4:
	latex $(project).tex
	bibtex $(project).aux
	latex $(project).tex
	latex $(project).tex
	dvips $(project).dvi
	ps2pdf $(project).ps

clear:
	rm -f *.out *.aux *.ps *.dvi *.log

