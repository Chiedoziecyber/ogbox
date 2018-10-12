
ogbox
=====

[![Build Status](https://travis-ci.org/oganm/ogbox.svg?branch=master)](https://travis-ci.org/oganm/ogbox)[![codecov.io](https://codecov.io/github/oganm/ogbox/coverage.svg?branch=master)](https://codecov.io/github/oganm/ogbox?branch=master)

A multi-purpose R package primarily for personal use

Installation
------------

    devtools::install_github('oganm/ogbox')

What's in the box?
------------------

There are many poorly documented functions here. Below are some examples separated by category.

### Developer tools

`getVersion`, `setVersion` and `setDate` functions allow manipulation of DESCRIPTION files. I use them for auto updating packages.

### List unpacking

Taken from [this](http://stackoverflow.com/questions/1826519/function-returning-more-than-one-value) github answer ages ago, this syntax

``` r
list[a,b] = list(c(1,2,3),c(4,5,6))
a
```

    ## [1] 1 2 3

``` r
b
```

    ## [1] 4 5 6

allows unpacking of lists. These days `zeallot` package does that with %&lt;-% operator.
