# 🎓 [AGH](https://www.agh.edu.pl/en) slide deck for [Quarto](https://quarto.org/docs/presentations/)/Jupyter/Python 🐍

This repo provides a single Jupyter/Python notebook file which can get you started with authoring a reproducible
  presentation in an template themed following [AGH University of Krakow](https://www.agh.edu.pl/en/) 
  [visual identity](https://www.agh.edu.pl/en/university/multimedia/graphic-symbol)
  and [logo usage](https://www.agh.edu.pl/en/o-agh/multimedia/znak-graficzny-agh/znak-graficzny-bez-nazwy) guidelines.
It allows to tightly couple the code generating all figures and values in the slides with other presentation content
  enabling you (or others) to recreate everything with one command and ensuring that slide contents are in sync
  with the codebase, in the spirit of "reproducible manuscripts" approach (see, e.g., [Perkel 2022, Nature](https://doi.org/10.1038/d41586-022-00563-z)).

To use it, grab the [example `.ipynb` file](https://github.com/habemus-python/quarto-agh-slides/blob/main/slides.ipynb) and edit it with your favourite Jupyter notebook tool.

To generate HTML files for presentation, do `quarto render slides.ipynb --execute --to revealjs`, the output should look like this:

<p align="center">
    <img 
        src="https://raw.githubusercontent.com/habemus-python/quarto-agh-slides/refs/heads/gif/slides.gif" 
        alt="slides converted to animated gif"
        width="75%"
    />
</p>

To convert it to a pdf, open in a browser, select `☰ :: Tools :: PDF Export Mode` and use the browser's print dialog to save a pdf.

## Quarto templates from other universities
- [monash.edu (Melbourne)](https://github.com/quarto-monash)
- [uu.nl (Utrecht)](https://github.com/UtrechtUniversity/uu-quarto-presentation-template)
- [ed.ac.uk (Edinburgh)](https://open.ed.ac.uk/how-to-make-a-professionally-sexy-quarto-presentation/)
- [warwick.ac.uk (Warwick)](https://github.com/warwick-stats-resources/warwickpres)
 
## Other AGH presentation templates
- [templates listed at the official agh.edu.pl page](https://www.agh.edu.pl/en/university/multimedia/presentation-templates)
