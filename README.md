# ElevDistr

<!-- badges: start -->
[![R-CMD-check](https://github.com/LivioBaetscher/ElevDistr/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/LivioBaetscher/ElevDistr/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->


ElevDistr is a method to calculate the distance to the climatic tree
line for large data sets of coordinates (WGS 84) with geographical
uncertainty. The default thresholds and the treeline definition is based
on Paulsen and Körner, Alp. Bot. 124: 1-12 (2014), users are free to
decide what climate layers they would like to use.

## Installation

The package ElevDistr can be installed via CRAN or from GitHub using the package [devtools](https://CRAN.R-project.org/package=devtools).  

Stable version from CRAN:
``` r
install.packages("ElevDistr")
library("ElevDistr")
```
Developmental from GitHub:
``` r
install.packages("devtools", repos = "http://cran.us.r-project.org")
devtools::install_github("LivioBaetscher/ElevDistr")
library("ElevDistr")
```

## Further information

A detailed description can be found on the [Wiki](https://github.com/LivioBaetscher/ElevDistr/wiki) or the package vignette.
