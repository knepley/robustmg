PRES_FIGS = /PETSc3/presentations-git/figures

all:
	TEXINPUTS=${TEXINPUTS}:${PRES_FIGS} BIBINPUTS=.:/PETSc3/papers/bibtexjb:${PETSC_DIR}/src/docs/tex:/Users/knepley/Documents latexmk -pdf robustmg.tex

clean:
	rm -f *.aux *.bcf *.bbl *.blg *.fdb_latexmk *.fls *.idx *.ilg *.ind *.log *.out *.run.xml *.toc robustmg.pdf

.PHONY: all
