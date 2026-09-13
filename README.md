# DSCI 571: Supervised Learning I

![DSCI 571: Supervised Learning I](book/img/571_banner.png)

Quarto book for the eight-lecture UBC Master of Data Science course, adapted from CPSC 330.

## Local use

Install Quarto and uv, then run `uv sync`. Run notebooks using the project environment with `book/` as their working directory. The introduction downloads pretrained model weights when executed; some tree visualizations also require the Graphviz system executable.

Run `quarto preview` to preview the book or `quarto render` to build HTML. Existing notebook outputs are retained; rendering is not a substitute for re-executing the examples.

## Adaptation status

The book is organized as an independent-study introduction (Chapter 0) followed by eight lecture chapters. Hyperparameter optimization is Chapter 6, linear models is Chapter 7, and Chapter 8 extends linear models with loss functions, multiclass classification, and a course conclusion. 

The preface and learning objectives describe the DSCI 571 scope. Course references within the chapters still need review. Existing acknowledgments and license notices are retained in `index.qmd`.

## Publishing

The copied GitHub Actions workflow publishes pushes to `main` to `gh-pages`. GitHub Pages must be configured for this new repository before the site is available.
