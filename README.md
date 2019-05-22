
<!-- README.md is generated from README.Rmd. Please edit that file -->

The data set, as a flat rectangular CSV file, can be downloaded from
[here](https://raw.githubusercontent.com/viparc/residues/master/data/last_week_antibiotics.csv):

``` r
# install.packages("readr")
last_week_antibiotics <- readr::read_csv("https://raw.githubusercontent.com/viparc/residues/master/data/last_week_antibiotics.csv",
                                         col_types = paste(c("c", rep("i", 47)), collapse = ""))
```
