# TeXification of "Gödel, Escher, Bach"

> This repository contains a $\TeX$ reproduction of the Russian translation\* of the book "Gödel, Escher, Bach: An Eternal Golden Braid" by [Douglas Hofstadter](https://en.wikipedia.org/wiki/Douglas_Hofstadter).

\* Д.Р. Хофштадтер "Гёдель, Эшер, Бах: эта бесконечная гирлянда".

### Build

[Render online](https://texlive2020.latexonline.cc/compile?git=https://github.com/Lipen/godel-escher-bach&target=main.tex&command=pdflatex)

Make it yourself:

```sh
latexmk -pdflatex main
```

### Work in progress

Currently, the plan is to finish transforming raw sources into TeX. This includes: copy-pasting text fragments, fixing typos (probably OCR artifacts), and reformatting text blocks, formulae, tables, illustrations, etc.

The next steps are: creating a decent page design, formatting the dialogues, adding an index, implementing some images using TikZ, adding a bibliography.

### Credits

- The source text in DOC format was taken from the site royallib.com.
- DOC sources were converted to LaTeX using [`pandoc`](https://pandoc.org/) utility.
- Illustrations were mostly found online, or screenshoted from the original ebook.
- Some illustrations were automagically upscaled and colorized using Photoshop.
