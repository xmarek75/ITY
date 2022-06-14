SHELL = /usr/bin/env bash
NAME = proj3
img1 = etiopan
img2 = oniisan
img3 = oniisan2



$(NAME):
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf -sPAPERSIZE=a4 $(NAME).ps
	rm -f $(NAME).dvi
	rm -f $(NAME).ps
	rm -f $(NAME).aux
	rm -f $(NAME).out
	rm -f $(NAME).log
    