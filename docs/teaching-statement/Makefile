all:
	pdflatex -shell-escape statement
	bibtex statement
	pdflatex -shell-escape statement
	pdflatex -shell-escape statement

haste:
	pdflatex -shell-escape statement
	open statement.pdf

clean:
	rm *.log *.aux *.bbl *.blg *.out
