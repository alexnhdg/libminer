
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

[![R-CMD-check](https://github.com/alexnhdg/libminer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/alexnhdg/libminer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.
It is a toy package created as part of a workshop and not meant for
serious use.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("alexnhdg/libminer")
```

## Example

To get a count of installed packages in each of your libraries,
optionally with the total sizes, use `lib_summary()`.

``` r
library(libminer)

lib_summary()
#>                                                                                        Library
#> 1                         /Library/Frameworks/R.framework/Versions/4.3-arm64/Resources/library
#> 2 /private/var/folders/l_/k4rkgyhd2ws0wsdf4kpzgycc0000gn/T/Rtmpva3Fjq/temp_libpath28a5419d4d25
#>   n_packages
#> 1        186
#> 2          1
#specify sizes = TRUE
lib_summary(sizes = TRUE)
#>                                                                                        Library
#> 1                         /Library/Frameworks/R.framework/Versions/4.3-arm64/Resources/library
#> 2 /private/var/folders/l_/k4rkgyhd2ws0wsdf4kpzgycc0000gn/T/Rtmpva3Fjq/temp_libpath28a5419d4d25
#>   n_packages   lib_size
#> 1        186 1136230711
#> 2          1      14695
```
