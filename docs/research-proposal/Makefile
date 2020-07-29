all:
	pdflatex -shell-escape proposal
	pdflatex -shell-escape proposal
	bibtex proposal
	bibtex proposal
	pdflatex -shell-escape proposal
	bibtex proposal
	pdflatex -shell-escape proposal

haste:
	pdflatex -shell-escape proposal

clean:
	rm *.log *.aux *.bbl
