# metcolor

An R interface for coloring metabolic maps drawn by [MetDraw](http://www.metdraw.com). This package can replace the `metcolor.py` command line tool.

## Installation

You can install the package using the `devtools` package:

```r
devtools::install_github("pauljensen/metcolor")

library(metcolor)
?metcolor
```

If you don't have the `devtools` package, you can download it from CRAN:

```r
install.packages("devtools")
```

## Usage

The package provides a single function, `metcolor`, that applies reaction or metabolite data (as data frames) to an SVG file produced by MetDraw. For details, see `?metcolor`.
