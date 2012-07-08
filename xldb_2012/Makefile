all: xldb_2012.pdf

xldb_2012.pdf: xldb_2012.tex images/*.png
	pdflatex xldb_2012 && pdflatex xldb_2012 && pdflatex xldb_2012

clean:
	rm -f *.{nav,log,aux,out,log,snm,toc,vrb}
