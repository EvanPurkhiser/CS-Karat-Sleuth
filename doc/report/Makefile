all: report.pdf

clean:
	rm -f report.pdf

report.pdf: report.md template.latex
	pandoc report.md -V links-as-notes -V geometry:margin=1in -V fontsize=11pt --template=template.latex -o report.pdf
