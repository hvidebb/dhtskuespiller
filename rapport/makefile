CC = pdflatex

main.pdf: *.tex
	$(CC) -synctex=1 main.tex

open: main.pdf
	vimura main.pdf
