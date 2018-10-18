PAPER=basedoc
# You want latexmk to *always* run, because make does not have all the info.
# Also, include non-file targets in .PHONY so they are run regardless of any
# file of the given name existing.
#.PHONY: 
#	pdflatex $(PAPER).tex
#	pdflatex $(PAPER).tex

$(PAPER).pdf:
	pdflatex -output-directory obj $(PAPER).tex 
	pdflatex -output-directory obj $(PAPER).tex 
clean:
	rm obj/*~ obj/*.log obj/*.aux obj/*.spl
