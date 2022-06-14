SHELL = /usr/bin/env bash
NAME = proj1
LOGIN = xmarek75



$(NAME):
	pdflatex $(NAME).tex
	dvips -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	rm -f $(NAME).aux
	rm -f $(NAME).out
	rm -f $(NAME).log
    