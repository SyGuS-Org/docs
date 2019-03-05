all: 
	pdflatex --shell-escape sygus
	bibtex sygus
	pdflatex --shell-escape sygus
clean:
	rm -f *~ *.aux *.bbl *.blg *.log *.out sygus.pdf *.dvi
