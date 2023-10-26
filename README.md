# UTSC-Notes

This is a repository of my course notes, created using LaTeX.

The documents have functional cross-referencing with links citing theorems and facts (GitHub's default
PDF viewer may not support this; you might have to download the files and use a different PDF viewer for clickable links).

There is also a fact list after the table of contents in each document (also with working links).

## LaTeX Configuration and Packages

The notes were made using the [MiKTeX-pdfTeX 4.11 (MiKTeX 22.10) TeX distribution](https://miktex.org/). VSCode was
used with the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension
(more information on [setting this up in VSCode](https://github.com/James-Yu/LaTeX-Workshop/wiki/Install) can be found
in its [wiki](https://github.com/James-Yu/LaTeX-Workshop/wiki)).

The following LaTeX packages used:

- `amsmath`, `amssymb`, `commath`, and `mathtools` &mdash; basic math symbols
- `derivative` &mdash; derivative and differential symbols
- `ntheorem` &mdash; enhanced theorem-like environments
- `cleveref` &mdash; enhanced cross-referencing (with definitions, theorems, etc.)
- `tcolorbox` &mdash; framed boxes for theorem-like environments
- `fancyhdr` &mdash; page headers
- `hyperref` &mdash; links in the table of contents and theorem/definition citations
- `graphicx` &mdash; images
- `algpseudocode` &mdash; pseudocode for algorithms
- `tikz` &mdash; diagrams for finite state automata

Various other packages such as `titlesec`, `parskip`, and `enumitem` were also used to tweak minor formatting options.
