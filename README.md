# Jeffrey Leung's SFU Coursework Notes

Notes from my SFU coursework, written in pdfLaTeX. (...mostly. One or two written in Microsoft Word.)

## Building the LaTeX Files

Install the base required LaTeX files:
```shell
sudo apt-get install texlive texlive-fonts-extra
```

In the directory of a specific course, build the file twice:
```shell
pdflatex FILE.tex
pdflatex FILE.tex
```

View the resulting generated PDF.
