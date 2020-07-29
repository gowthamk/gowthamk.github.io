all:
	pdflatex -shell-escape statement
	pdflatex -shell-escape statement
	bibtex statement
	bibtex statement
	pdflatex -shell-escape statement
	bibtex statement
	pdflatex -shell-escape statement
	open statement.pdf

haste:
	pdflatex -shell-escape statement
	open statement.pdf

clean:
	rm *.log *.aux *.bbl
