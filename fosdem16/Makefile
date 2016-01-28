pres.pdf: pres.tex
	xelatex --shell-escape -synctex=1 pres.tex
	xelatex --shell-escape -synctex=1 pres.tex

all: pres.pdf

show: pres.pdf
	mupdf pres.pdf ${PAGE}

clean:
	rm -f *.blg *.bbl *.log *.aux *.nav *.out *.toc *.snm *.synctex.gz *.vrb

distclean: clean
	rm *.pdf
