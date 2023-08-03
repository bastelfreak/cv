# README for bastelfreaks CV


Hi! this repository contains my CV, my Curriculum Vitae. A German version exists
in the [content-de.pdf](https://github.com/bastelfreak/cv/blob/master/content-de.pdf)
file, the English version in [content-en.pdf](https://github.com/bastelfreak/cv/blob/master/content-en.pdf).

You need a few archlinux packages to build it:

```bash
pacman -Syu texlive-bin texlive-binextra texlive-luatex texlive-fontsextra ttf-octicons ttf-font-awesome-4
```

Build the document:

```bash
latexmk -pdf -lualatex content-en.tex
latexmk -pdf -lualatex content-de.tex
```

Thanks to [Raphaël Pinson](https://raphink.info/) who wrote most of the Latex code for his own
[CV](https://github.com/raphink/CV/blob/master/RaphaelPinson_en.pdf?raw=true).

As you can see in my CV, I'm involved in the Puppet ecosystem since several
years. I offer Puppet consulting and development. Write to
[tim@bastelfreak.de][mailto:tim@bastelfreak.de] for an inquiry if you're
interested.
