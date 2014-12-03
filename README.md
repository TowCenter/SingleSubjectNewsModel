.tex file manually created from .pdf

generate html w/pandoc:

pandoc SingleSubject.tex -o SingleSubject.html

Create CMS-ready files:
python CreateRightRail.py SingleSubject.html


generate md w/pandoc:

pandoc SingleSubject.tex -o SingleSubject.md

Generate GitBook files:
python GenerateGitBook.py SingleSubject.html

