CMD=pdflatex


all: Resume_Swetosree.pdf Resume.pdf Resume_Job.pdf Coverletter.pdf 
Resume: Resume.pdf
Resume_Job: Resume_Job.pdf
Resume_Swetosree: Resume_Swetosree.pdf

%.pdf: %.tex
	$(CMD) $<

clean:
	rm -rf *.dvi  *.log *.ps *.aux *.out 
remjunk:
	rm -rf *.dvi  *.log *.ps *.aux *.out 
