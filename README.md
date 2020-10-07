# University of Auckland PhD Thesis Rmarkdown Template

This repository provides a template for a University of Auckland PhD thesis using Rmarkdown with the {bookdown} package, modified based on [robjhyndman/MonashThesis](https://github.com/robjhyndman/MonashThesis).

## Requirements

To set up the software, you will need to install the {bookdown} package and its dependencies as follows:

```r
install.packages('bookdown')
```

You will also need LaTeX installed. If you don't already have LaTeX, one convenient approach is to install it via R:

```r
install.packages('tinytex')
tinytex::install_tinytex()
```
