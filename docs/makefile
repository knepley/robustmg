PRES_FIGS = ./figures

all:
	TEXINPUTS=${TEXINPUTS}:${PRES_FIGS} BIBINPUTS=.:${PETSC_DIR}/src/docs/tex latexmk -pdf robustmg.tex

clean:
	rm -f *.aux *.bcf *.bbl *.blg *.fdb_latexmk *.fls *.idx *.ilg *.ind *.log *.out *.run.xml *.toc robustmg.pdf

.PHONY: all
