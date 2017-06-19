# README

This is a repository to build my CV. You need a few archlinux packages for this:

```bash
pacman -Syu texlive-bin ttf-octicons texlive-fontsextra
```

Build the document:

```
latexmk -lualatex -pdf content-en.tex
```
