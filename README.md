## GENERAL

This is a LaTex document template, specifically targeted towards
student of the university of applied sciences Munich (Hochschule München)

To compile this you will have to run a latex compiler (like pdflatex) once at the beginning
and once at the end, after your extra compilers have done their stuff.
This extra stuff needs to be at least once makeglossaries. Additionally run
bibtex if you wanna use .bib sources.

Subfiles structure allows you to compile one of the single tex files other than
the main individually. For this only run a latex compiler once, as extras like makeglossaries
and bibtex will not work without the latex code in "main.tex".

For example i generated my pdf by running pdflatex, makeglossaries, pdflatex

## SOURCES

[1] http://www.macfreek.nl/memory/LaTeX_package_conflicts#Caption_and_Subfig\
[2] https://stackoverflow.com/questions/3828566/list-of-footnotes-in-latex\
[3] https://tex.stackexchange.com/questions/65127/extra-vertical-space-after-hline-causes-a-gap-in-the-right-border-of-an-array\
[4] https://www.overleaf.com/learn/latex/Code_listing

## LICENSE

MIT License

Copyright (c) [2022] [D.Hainsch]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.