
# libminer

<!-- badges: start -->
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.
It is a toy package created as part of a workshop and not meant for serious use.

## Installation

You can install the development version of libminer from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("alexnhdg/libminer")
```

## Example

To get a count of installed packages in each of your libraries, optionally
with the total sizes, use `lib_summary()`.

``` r
library(libminer)

lib_summary()
#specify sizes = TRUE
lib_summary(sizes = TRUE)
```

