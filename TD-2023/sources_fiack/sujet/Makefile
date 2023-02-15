FILE=main
SRC=./src

DEMO_DIR=./demo
DEMO=demo

all: $(FILE).pdf

$(FILE).pdf: $(SRC)/$(FILE).tex
	pdflatex -shell-escape $(SRC)/$(FILE).tex
	pdflatex -shell-escape $(SRC)/$(FILE).tex

demo: $(DEMO).pdf

$(DEMO).pdf: $(DEMO_DIR)/$(DEMO).tex
	pdflatex $(DEMO_DIR)/$(DEMO).tex
	pdflatex $(DEMO_DIR)/$(DEMO).tex

okular: $(FILE).pdf
	okular $(FILE).pdf &
	
evince: $(FILE).pdf
	evince $(FILE).pdf &

clean:
	rm -f $(FILE).aux $(FILE).log $(FILE).out $(FILE).bbl $(FILE).blg $(FILE).toc 
	rm -f $(FILE).nav $(FILE).snm
	rm -rf _minted-$(FILE) $(FILE).vrb
	rm -f $(DEMO).aux $(DEMO).log $(DEMO).out $(DEMO).bbl $(DEMO).blg $(DEMO).toc 
	rm -f $(DEMO).nav $(DEMO).snm

mrproper: clean
	rm -f $(FILE).pdf
	rm -f $(DEMO).pdf
