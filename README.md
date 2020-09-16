# TMwR

[![Netlify Status](https://api.netlify.com/api/v1/badges/a0db3b22-8c6f-40e8-bcef-9de2f99fd428/deploy-status)](https://app.netlify.com/sites/tidy-models-with-r/deploys)

This repository contains the source for [_Tidy Modeling with R_](https://tmwr.org). The purpose of this book is to demonstrate how the [tidyverse](https://www.tidyverse.org/) and [tidymodels](https://www.tidymodels.org/) can be used to produce high quality models.

# Reproducing the book or results

First, you'll need to install the required packages. To do this, first install the `remotes` package:

``` r
install.packages("remotes")
```

Then use this to install what you need to create the book: 

``` r
remotes::install_github("tidymodels/TMwR")
```

Although we rigorously try to use the current CRAN versions of all packages, the code above may install some development versions. 

The content is created using the `bookdown` package. To compile the book, use:

```r
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

This will create the HTML files in a directory called `_book`. 


# Contributing

This project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.

_Tidy Modeling with R_ is currently a work in progress. As we create it, the code here is updated. This openness also allows users to contribute if they wish. Most often, this comes in the form of correcting typos, grammar, and other aspects of our work that could use improvement. Instructions for making contributions can be found in the [`contributing.md`](https://github.com/tidymodels/TMwR/blob/master/contributing.md) file.
