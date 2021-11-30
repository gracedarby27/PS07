Grace Darby - PS07
================

## GitHub Documents

This is an R Markdown format used for publishing markdown documents to
GitHub. When you click the **Knit** button all R code chunks are run and
a markdown file (.md) suitable for publishing to GitHub is generated.

## Including Code

You can include R code in the document as follows:

``` r
library(tidyverse)
```

    ## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.1 ──

    ## ✓ ggplot2 3.3.5     ✓ purrr   0.3.4
    ## ✓ tibble  3.1.4     ✓ dplyr   1.0.7
    ## ✓ tidyr   1.1.3     ✓ stringr 1.4.0
    ## ✓ readr   2.0.2     ✓ forcats 0.5.1

    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
alphabet_position <- tibble(
  letter = c("S", "A", "L", "M", "O", "N"),
  number = c(19, 1, 12, 13, 15, 14)
)

alphabet_position
```

    ## # A tibble: 6 × 2
    ##   letter number
    ##   <chr>   <dbl>
    ## 1 S          19
    ## 2 A           1
    ## 3 L          12
    ## 4 M          13
    ## 5 O          15
    ## 6 N          14

## Including Plots

You can also embed plots, for example:

![](README_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
