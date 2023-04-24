
<!-- README.md is generated from README.Rmd. Please edit that file -->

# stac4cast

<!-- badges: start -->

[![R-CMD-check](https://github.com/eco4cast/stac4cast/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/eco4cast/stac4cast/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of stac4cast is to generate [STAC](https://stacspec.org/en)
catalogs for forecasts.

## Installation

You can install the development version of stac4cast from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("eco4cast/stac4cast")
```

## Overview

The STAC metadata standard essentially defines three levels of objects:

- Items
- Catalogs
- Collections

An item is a core atomic unit of data. A catalog is a list of items, a
collection is an extension of a catalog that adds additional metadata.
These objects are represented as JSON files on a static website, linked
by URLs. Once created, STAC can be visualized and explored using tools
such as [stac browser](https://radiantearth.github.io/stac-browser/#/)
and queried programmatically with packages such as
[rstac](https://cran.r-project.org/web/packages/rstac)

## Getting started

``` r
library(stac4cast)
```

See the [examples
directory](https://github.com/eco4cast/stac4cast/tree/main/inst/examples)
for current examples.
