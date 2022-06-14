SHELL = /usr/bin/env bash
PROJ=proj4
NAME=proj4

$(NAME).pdf: $(NAME).ps
		pdflatex $(NAME).tex

$(NAME).ps: $(NAME).dvi
		dvips -sPAPERSIZE=a4 $(NAME).dvi

$(NAME).dvi: $(NAME).tex 
		latex $(NAME).tex
		bibtex $(NAME)
		latex $(NAME).tex
		latex $(NAME).tex
clean:
		-rm $(NAME).ps $(NAME).dvi $(NAME).aux  $(NAME).log $(NAME).out $(NAME).bbl $(NAME).blg
zip:
		zip xmarek75-fit.zip $(NAME).tex Makefile czechiso.bst $(NAME).bib