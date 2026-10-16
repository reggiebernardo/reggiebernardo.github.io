bibfiles=$(wildcard *.bib)
epsfigs=$(wildcard plots/*.eps)
pdffigs=${epsfigs:.eps=.pdf}
pngfigs=$(wildcard plots/*.png)

texfiles=main.tex
basename=$(texfiles:.tex=)
texpdffiles=${texfiles:.tex=.pdf}

PDFLATEX = pdflatex -file-line-error -halt-on-error

$(texpdffiles):	%.pdf: %.tex $(bibfiles) $(pdffigs) $(pngfigs)
		$(PDFLATEX) $<
		bibtex $(basename)
		$(PDFLATEX) $<
		$(PDFLATEX) $<
		open main.pdf
	
$(pdffigs):	%.pdf: %.eps
		epspdf $<

clean:
		rm -f main.pdf *.aux *.log *.bbl *.blg mainNotes.bib
