# resume
Piper Thunstrom professional resume source

When rendering with pandoc, add `\pagenumbering{gobble}` to line 1 of 
`resume.md` to remove line numbers.

    pandoc Thunstrom-Piper-resume.md --pdf-engine=xelatex -V geometry:margin=1in -V linestretch:1.35 -o resume.pdf
