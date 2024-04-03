
<!-- README.md is generated from README.Rmd. Please edit that file -->

# planner <img src="man/figures/logo.png" align="right" style="float:right; height:120px;"/>

<!-- badges: start -->

[![R CMD
Check](https://github.com/frbcesab/planner/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/frbcesab/planner/actions/workflows/R-CMD-check.yaml)
[![Website](https://github.com/frbcesab/planner/actions/workflows/pkgdown.yaml/badge.svg)](https://github.com/frbcesab/planner/actions/workflows/pkgdown.yaml)
[![License: GPL (\>=
2)](https://img.shields.io/badge/License-GPL%20%28%3E%3D%202%29-blue.svg)](https://choosealicense.com/licenses/gpl-2.0/)
<!-- badges: end -->

<p align="left">
• <a href="#overview">Overview</a><br> •
<a href="#installation">Installation</a><br> •
<a href="#get-started">Get started</a><br> •
<a href="#citation">Citation</a><br> •
<a href="#contributing">Contributing</a><br> •
<a href="#acknowledgments">Acknowledgments</a>
</p>

## Overview

The R package `planner` is dedicated to create a monthly calendar. It
plots and exports the calendar as a `pdf` file (ready to print in the A4
paper format). Holidays (only France is supported yet) are identified
and user can easily add events (up to four by day). User can also choose
between of a week of five days (working week) or a full week (weekend
included).

- **Empty monthly calendar (with weekends)**

![](man/figures/calendar-demo-1.png)

<br/>

- **Empty monthly calendar (without weekend)**

![](man/figures/calendar-demo-2.png)

<br/>

- **Monthly calendar with single-day events**

![](man/figures/calendar-demo-3.png)

<br/>

- **Monthly calendar with multi-day events**

![](man/figures/calendar-demo-4.png)

<br/>

- **Monthly calendar with multi-week events**

![](man/figures/calendar-demo-5.png)

<br/>

- **All-in-one**

![](man/figures/calendar-demo-6.png)

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
## Install < remotes > package (if not already installed) ----
if (!requireNamespace("remotes", quietly = TRUE)) {
  install.packages("remotes")
}

## Install < planner > from GitHub ----
remotes::install_github("frbcesab/planner")
```

Then you can attach the package `planner`:

``` r
library("planner")
```

## Get started

For an overview of the main features of `planner`, please read the [Get
started](https://frbcesab.github.io/planner/articles/planner.html)
vignette.

## Citation

Please cite `planner` as:

> Casajus Nicolas (2024) planner: An R package to create a monthly
> calendar. R package version 0.0.0.9000.
> <https://github.com/frbcesab/planner/>

## Contributing

All types of contributions are encouraged and valued. For more
information, check out our [Contributor
Guidelines](https://github.com/frbcesab/planner/blob/main/CONTRIBUTING.md).

Please note that the `planner` project is released with a [Contributor
Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.

## Acknowledgments

This package has been developed as part of a
[FRB-CESAB](https://www.fondationbiodiversite.fr/en/about-the-foundation/le-cesab/)
work.
