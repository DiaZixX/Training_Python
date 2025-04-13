TEXFILE = cours_python.tex
PDF = $(TEXFILE:.tex=.pdf)

compile:
	pdflatex -shell-escape $(TEXFILE)

view: compile
	atril $(PDF)

clean:
	rm -f *.aux *.log *.out *.toc *.lof *.lot
