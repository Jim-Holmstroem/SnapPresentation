# dependencies: sudo pacman -S pygmentize
build: clean
	pdflatex --shell-escape presentation.tex


clean:
	rm -rf *.nav *.snm *.pdf *.aux *.log *.out *.toc _minted-presentation/ || true

run:
	apvlv presentation.pdf
