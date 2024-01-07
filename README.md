
<p align="center">
<img src="man/figures/tinytable_logo.png" height = "250" class = "center">
</p>

<br> <!-- badges: start --> <!-- badges: end -->

## What?

`tinytable` is a small but powerful `R` package to draw LaTeX/PDF, HTML,
Markdown, and Typst tables. The interface is minimalist, but it gives
users direct access to powerful frameworks to create endlessly
customizable tables: `tabularray` for LaTeX/PDF and Bootstrap for HTML.

## Why?

The core design philosophy rests on three pillars:

1.  Data is separate from style.
2.  Tables should be deeply customizable.
3.  [Lightweight is the right weight.](https://www.tinyverse.org/)

There are several senses in which `tinytable` is “light,” and this
brings many benefits to users and developers:

-   The user interface is simple, streamlined, consistent, uncluttered.
-   `tinytable` is a thin wrapper around incredibly powerful frameworks:
    Bootstrap for HTML and `tabularray` for LaTeX/PDF. By providing
    quick and easy access to those frameworks, `tinytable` allows users
    to create endlessly customizable tables:.
-   The `tinytable` code base is very small and easy to maintain.
-   `tinytable` does not rely on any other `R` package. In contrast,
    `kableExtra` uses 66 dependencies, and `gt` imports 65 other
    packages every time it is loaded.
-   This package is free. The price is tiny!

## Installation

You can install the development version of tinytable from
[GitHub](https://github.com/) with:

``` r
remotes::install_github("vincentarelbundock/tinytable")
```

## Get started

TODO
