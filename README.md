# A PhD Thesis template

This is the template that I used for my PhD thesis at the University of Sussex. I created this template so that others can reuse in the future for their thesis. The whole template is released under a MIT license.

This template builds upon previous templates I made for my BSc and MSc thesis. I also took some inspiration from [Fabrizio's](https://github.com/fabriziomiano/phd_thesis) excellent Latex template.

I ensured that this template is compatible to the PhD thesis format expected by University of Sussex PhD students, but it might be useful for PhD students of other Universities as well. The Phd template assumes a PhD by publication style!

## Criteria

Sussex has [few](https://www.sussex.ac.uk/rsao/examination/) formal requirements on layout and presentation, but there are some criteria for layouting.

* No restrictions on typeface but it should be clear and easy to read
* Minimum font size of not less than 9 for figures (I will make use of 11 for captions and 12 throughout)
* Main text double or one-and-a-half line-spacing (footnotes and quotes single line-spacing)
* Margins: (left 4cm, top and bottom 2.5 and right 2cm)
* Pages should be numbered consecutively and located centrally at the top (seems odd, why not the bottom?) of the page.

There are also a number of mandatory pages for a PhD thesis (Title page, Table of contents,...) and I have created default templates for these.

## Usage

I made this template on Linux using mainly Latexila. To compile this thesis run in sequence:

- pdflatex main.tex  
- bibtex main
- pdflatex main.tex (x2)

Alternatively upload to [overleaf](www.overleaf.com) which also has an easy to use interface to load and compile Tex documents.
