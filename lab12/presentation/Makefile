# FILES=$(patsubst %.*, %., main.tex)
# FILES += $(patsubst %.md, %.pdf, $(wildcard *.md))
all:
	pdflatex --shell-escape presentation -interaction=scrollmode
draft:
	pdflatex --shell-escape presentation -interaction=scrollmode -draftmode

print:
	ls main.*
