SHELL = /usr/bin/env bash
NAME = proj3




$(NAME):
	latex $(NAME).tex
	latex $(NAME).tex
	dvips -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps
	pdflatex $(NAME).tex
	rm -f $(NAME).aux
	rm -f $(NAME).out
	rm -f $(NAME).log
	rm -f $(NAME).dvi
    