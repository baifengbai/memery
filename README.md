
<!-- README.md is generated from README.Rmd. Please edit that file -->
memery
======

[![Travis-CI Build Status](https://travis-ci.org/leonawicz/memery.svg?branch=master)](https://travis-ci.org/leonawicz/memery) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/leonawicz/memery?branch=master&svg=true)](https://ci.appveyor.com/project/leonawicz/memery) [![Coverage Status](https://img.shields.io/codecov/c/github/leonawicz/memery/master.svg)](https://codecov.io/github/leonawicz/memery?branch=master)

The `memery` package is used for generating internet memes suited specifically to data analysts. `merery` offers the following:

-   Memes can use jpg or png inputs for the background image.
-   You can control the font family.
-   The classic meme font family, Impact, with shadow/outline effect for the meme text label is available as the default.
-   Shadow effect is available for other fonts as well.
-   Arbitrary number of text labels and placement using vectorized arguments; ideal for top/bottom or title/subtitle meme text pairs.
-   Memes may optionally include a superimposed inset plot (ggplot object).
    -   The default is to draw the optional plot directly on top of the background image, so it is recommended to use a transparent or semi-transparent background color for the ggplot panel and plot regions.
    -   Alternatively, if you want an opaque background for the plot inset, size and placement can be adjusted to your needs.
-   Output file can be jpg or png.

![](docs/articles/meme4d.jpg)

Installation
------------

You can install memery from github with:

``` r
# install.packages('devtools')
devtools::install_github("leonawicz/memery")
```

See the [vignette](https://leonawicz.github.io/memery/articles/memery.html) for an overview with usage examples.
