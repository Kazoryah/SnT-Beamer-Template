# SnT Beamer Template
> _Contact_ **Romain Hermary [<romain.hermary@uni.lu>]**

A template for _**Beamer**_ presentations with the _**SnT**_ styling.

## Some Details

This template is based on the _**LCSB**_ template (available on their [repository](https://git-r3lab.uni.lu/R3/outreach/templates/presentations/latex/-/tree/master)), and adapted to _**SnT**_ using an available **PDF** on the center's [web page](https://wwwfr.uni.lu/snt/about_us/snt_presentation).

It is possible to use it directly on _**Overleaf**_, by importing it as a **ZIP** file, or by copying the [shared](https://www.overleaf.com/read/xtwkbrpzpkth) project directly. Obviously, you can also compile it your preferred way; in any case, the _**LuaLaTex**_ compiler is required.

The [`main.tex`](main.tex) is empty, for you to start with a fresh project directly. Another main document ([`example_main.tex`](example_main.tex)) derived from the original _**LCSB**_ one is provided, with a great amount of useful examples, as well as a dummy bibliography file [`example_bib.bib`](example_bib.bib) -- they both can be removed safely when you do not need them anymore, the [`main.tex`](main.tex) file is already linked to [`bib.bib`](bib.bib).

Compiled version of the example document is available ([`SnT_Beamer_Template.pdf`](SnT_Beamer_Template.pdf)) for a complete overview.

## Updates Over Base Theme
> Mentioned slides are the ones from the compiled version of `example_main.tex`.

- Theme images, logos, naming...
- _**SnT**_ colors definition (`snt blue`, `snt red`...) -- see [`/theme/sntcolors.sty`](/theme/sntcolors.sty)
- Changed math style to `serif` -- slide 10
- New command `\forward{}` to easily make text pop out -- slide 10
- `\blfootnote{}` for a note at the bottom of the slide -- slide 10
- Addition of subsection pages -- the two slides after page 7
- Table of content example -- slide 2
- Block styling -- slide 5
- **Tikz** tree examples -- slides 6 and 7
- Reference management and section page -- see after slide 12
- Appendix slides and numbering -- see last slides

## Latest Update

- New citation style, with numbered regerences and the possibility to add the citation at the bottom of the page (`\citef{}`), and other custom citation styles (`\citea{}`, `\citep{}`...) -- slide 11
- Removed references slides numbering
- Use of datetime package -- see title page
