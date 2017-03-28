CC = pdflatex

main.pdf: *.tex */*.tex
	$(CC) -synctex=1 main.tex

open: main.pdf
	vimura main.pdf
