# FILES=$(patsubst %.*, %., main.tex)
# FILES += $(patsubst %.md, %.pdf, $(wildcard *.md))
all:
	pdflatex --shell-escape report  -interaction=scrollmode

draft:
	pdflatex --shell-escape report -interaction=scrollmode -draftmode

print:
	ls main.*
