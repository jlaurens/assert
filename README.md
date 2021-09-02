# assert
 Lightweight assertion framework for LaTeX

## To build the style
```
pdflatex assert.ins
```
## To build the doc
```
pdflatex assert.dtx;makeindex -s gind.ist assert.dtx;pdflatex assert.dtx;pdflatex assert.dtx
pdflatex assert-doc;makeindex -s gind.ist assert-doc;pdflatex assert-doc;pdflatex assert-doc
pdflatex assert-code;makeindex -s gind.ist assert-code;pdflatex assert-code;pdflatex assert-code
```
## To test
```
pdflatex assert-test
```
