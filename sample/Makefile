FILE=vol_082

all: $(FILE).pdf

$(FILE).pdf: $(FILE).tex ../xelatexhanaminvertical.sty
	xelatex $< && xelatex $<

.PHONY: clean
clean:
	rm -f $(FILE).aux $(FILE).log $(FILE).dvi $(FILE).toc $(FILE).out $(FILE).pdf
