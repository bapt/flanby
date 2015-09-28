pres.pdf: pres.tex
	xelatex --shell-escape -synctex=1 pres.tex
	xelatex --shell-escape -synctex=1 pres.tex

all: pres.pdf

show: pres.pdf
	zathura pres.pdf ${PAGE}

clean:
	rm -f *.blg *.bbl *.log *.aux *.nav *.out *.toc *.snm *.synctex.gz

distclean: clean
	rm *.pdf
