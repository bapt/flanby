pres.pdf: pres.tex
	pdflatex --shell-escape -synctex=1 pres.tex
	pdflatex --shell-escape -synctex=1 pres.tex

all: pres.pdf

show: pres.pdf
	xpdf pres.pdf ${PAGE}

clean:
	rm -f *.blg *.bbl *.log *.aux *.nav *.out *.toc *.snm *.synctex.gz

distclean: clean
	rm *.pdf
