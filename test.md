Lab 02 - Take a sad plot and make it better
================
INSERT TEAM NAME HERE
2020-10-23

``` r
library(tidyverse)
```

    ## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.0 ──

    ## ✓ ggplot2 3.3.2     ✓ purrr   0.3.4
    ## ✓ tibble  3.0.4     ✓ dplyr   1.0.2
    ## ✓ tidyr   1.1.2     ✓ stringr 1.4.0
    ## ✓ readr   1.3.1     ✓ forcats 0.5.0

    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
achieve <- read_csv("data/StudentsPerformance.csv")
```

    ## Parsed with column specification:
    ## cols(
    ##   gender = col_character(),
    ##   `race/ethnicity` = col_character(),
    ##   `parental level of education` = col_character(),
    ##   lunch = col_character(),
    ##   `test preparation course` = col_character(),
    ##   `math score` = col_double(),
    ##   `reading score` = col_double(),
    ##   `writing score` = col_double()
    ## )

``` r
dim (achieve)
```

    ## [1] 1000    8
