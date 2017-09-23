CMD=pdflatex


all: Resume_Sweto.pdf Resume.pdf Resume_Job.pdf Coverletter.pdf 
Resume: Resume.pdf
Resume_Job: Resume_Job.pdf
Resume_Sweto: Resume_Sweto.pdf

%.pdf: %.tex
	$(CMD) $<

clean:
	rm -rf *.dvi  *.log *.ps *.aux *.out 
remjunk:
	rm -rf *.dvi  *.log *.ps *.aux *.out 
