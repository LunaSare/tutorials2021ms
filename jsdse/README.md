# Template for Journal of Statistics and Data Science Education

Downloaded from https://www.tandf.co.uk/journals/authors/uJSELaTeX.zip
at https://amstat.tandfonline.com/action/authorSubmission?journalCode=ujse20&page=instructions#.VFkuMPnF_0c

To render the JSDSE version:

```
cd jsdse

R -e 'tools::texi2pdf(file = "TAS-template.tex", clean=TRUE)'

mv jsdse/TAS-template.pdf jsdse/Manuscript_with_author_details.pdf

mv jsdse/TAS-template.pdf jsdse/Manuscript_anonymous.pdf

cd ..
```
