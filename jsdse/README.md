# Template for Journal of Statistics and Data Science Education

Downloaded from https://www.tandf.co.uk/journals/authors/uJSELaTeX.zip
at https://amstat.tandfonline.com/action/authorSubmission?journalCode=ujse20&page=instructions#.VFkuMPnF_0c

To render the JSDSE version do:

```
cd jsdse

R -e 'tools::texi2pdf(file = "Manuscript.tex", clean=TRUE)'

cd ..
```

If rendering the manuscript pdf version with author details, make sure to set "0"
on line 13 of Manuscript.tex, then do:

```
cd jsdse
R -e 'tools::texi2pdf(file = "Manuscript.tex", clean=TRUE)'
mv Manuscript.pdf Manuscript_with_author_details.pdf
cd ..
```

If rendering the blind version of manuscript pdf, change "0" to "1" on line 13
of Manuscript.tex, and do:

```
cd jsdse
R -e 'tools::texi2pdf(file = "Manuscript.tex", clean=TRUE)'
mv Manuscript.pdf Manuscript_blind.pdf
cd ..
```
