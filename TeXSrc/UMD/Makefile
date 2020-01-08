JobName=Maryland_SoP
TeX=pdflatex
LatexFlags= -jobname=$(JobName) --shell-escape

default:
	make build
	make build
	make clean

build:
	$(TeX) $(LatexFlags) src.tex

clean:
	rm -f $(JobName).log $(JobName).aux $(JobName).out $(JobName).toc
	rm -rf _minted-*
