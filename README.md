
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tidybiology

<!-- badges: start -->

<!-- badges: end -->

This package accompanies a workshop-style class that provides an
introduction to the emerging field of Data Science in R, including data
analysis and visualization, with a particular focus on its utility for
biological insight. In class, students will be provided with biological
datasets using this package, and introduced to the `tidyverse` and
`code` used to examine data. In the first half of each class, students
will be lectured on methods and shown demonstrations; in the second half
of each class, students will use tools to analyze real data. Methods for
filtering, sorting, and transforming data will be discussed along with
visualization tools and options. Particular attention will be paid to
code interpretation and data provenance methods by learning to generate
reproducible data output files. For a final project, students will be
given a new dataset to analyze using the tools learned during the
course, and will share findings with the class in a short oral
presentation. Although specific datasets will be used for analysis in
class, this workshop will provide broadly applicable tools to
reproducibly analyze and visualize data across the biological sciences.

## Installation

You **cannot** yet install the released version of tidybiology from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("tidybiology")
```

So in the meantime, use the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("hirscheylab/tidybiology")
```

## Example

To see the datasets contained within this package:

``` r
#to load the library
library(tidybiology)

#to see the datasets within this package
data(package = "tidybiology")

#to load a dataset
data(simplechromosome)

#simple plot
plot(simplechromosome, xlab = "Chromosome", ylab = "Number of Basepairs")
```

<img src="man/figures/README-example-1.png" width="100%" />
