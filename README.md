
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypkgr

<!-- badges: start -->

[![R-CMD-check](https://github.com/tomorrowgaarusa/mypkg_takashi/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/tomorrowgaarusa/mypkg_takashi/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of mypkgr is to master the Rsutdio and git ! I cloned it into
/home/nodapai/mypkgr on Ubuntsu and /Documents/mypkgr on Macs

## Installation

You can install the development version of mypkgr from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("tomorrowgaarusa/mypkg_takashi")
```

## Example

This is a basic example which shows you how to solve a common problem:
Hello. This is git practice from takashi and This helps researchers keep
track on their workflow

> > > > > > > c473fa838570f11b78407274028f12f65b594750

``` r
x <- c(3, 4)
y <- c(2, 3)
z = x-y
print(z)
#> [1] 1 1
## basic example code
```

<!-- What is special about using `README.Rmd` instead of just `README.md`? You can include R chunks like so: -->

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
