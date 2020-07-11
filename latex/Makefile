.DEFAULT_GOAL := all

all: kvlasov.pdf

%.pdf: %.tex
	latexmk -pdf $<

clean:
	rm -rf *.pdf *.out *.log *.aux *.fdb_latexmk *.fls

