TX=comps

$(TX).pdf: $(TX).tex
	pdflatex $(TX).tex && bibtex $(TX).aux && pdflatex $(TX).tex && pdflatex $(TX).tex

