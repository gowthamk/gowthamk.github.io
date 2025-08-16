
all:
	pdflatex "\def\genrefs{1} \input{cv.tex}"
	pdflatex "\def\genrefs{1} \input{cv.tex}"
	mv cv.pdf cv_with_ref.pdf
	pdflatex cv
	pdflatex cv

haste:
	pdflatex cv
	open cv.pdf

clean:
	rm -f *~ *.aux *.out *.log *.fdb_latexmk *.fls *.synctex.gz
