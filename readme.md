# LaTeX Template of the Chair of Enterprise Systems

Version 0.91

# What is LaTeX?

LaTeX is a high-quality typesetting system; it includes features designed for the production of technical and scientific documentation. LaTeX is the de facto standard for the communication and publication of scientific documents. (Source [The LaTeX Project](https://www.latex-project.org/) )

### How to start with LaTeX

LaTeX is fairly easy to learn in a short amount of time. For newbies we recommend to start with the [learn LaTeX in 30 Minutes](https://de.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes) tutorial. If you are looking for more detailed information please check the
[detailed documentation](https://de.overleaf.com/learn/latex/Tutorials).

Remark: For a quick-start we recommend to use the online LaTeX editor [Overleaf](https://www.overleaf.com/), since you do not to install anything locally.

## Recommended Editors

| Editor   | Link                             | Type    | Recommended |
| -------- | -------------------------------- | ------- | ----------- |
| Overleaf | https://www.overleaf.com/        | online  | yes         |
| TeXMaker | http://www.xm1math.net/texmaker/ | offline | no          |

#### Overleaf

Overleaf is an online, colaborative LaTeX editor which allows you so start working on your thesis right away, without installation.

1. Upload whole template folder (remark: including "fonts" and "images" subfolders)
   - Overleaf: "upload" (top-left) -> Select all contents of template folder
2. Make sure XeLaTeX is selected as Latex Compiler
   - Overleaf: "Menu" (top-left) -> Compiler -> Select "XeLaTeX"
3. Make sure "main.tex" is select as Main document
   - Overleaf: "Menu" (top-left) -> Main document -> Select "main.tex"

#### TexMaker

More experienced users, who want to edit their documents offline, can use TeXMaker. For this please download [TeXMaker](http://www.xm1math.net/texmaker/) and install it on your system.

Afterwards it is important execute the compilation steps in the right order:

1. run XeLaTeX
   - creates a PDF without biblipgraphy and abbreviations (not final)
2. run bibtex
   - to create bibliography entries
3. run makeindex
   - to create abbreviations section
4. re-run XeLaTeX
   - creates the final PDF

## File structure

- main.tex
  - add your content here
- bibliography.bib
  - add your references in bibtex (library of journals, articles, books, etc cited)
  - Remark 1: most reference mangement softwares (e.g. Zotero) allow you a copy+paste ready export of your references in bibtex
  - Remark 2: your references from the bibliography.bib will only show up in the Bibliography section of your document if you cite them (e.g. \cite{hoehle_espoused_2015})
- settings.tex
  - DO NOT EDIT
  - contains document formating, settings and functions
- /images/ (folder)
  - add your diagram, pictures, charts, etc. preferably in PNG format
  - contains university logo and example pictures
- /fonts/ (folder)
  - DO NOT EDIT
  - contains Times New Roman font

## Feedback, Questions & Remarks

Thank you for using our LaTeX template. In case you have feedback, questions or remarks please feel free to contact the authors. Please understand that we cant offer 24/7 support.

| Name                          | eMail                      |
| ----------------------------- | -------------------------- |
| Markus Dietsche (author)      | dietsche.markus@gmail.com  |
| Fareed Zandkarimi (co-author) | zandkarimi@uni-mannheim.de | offline |
