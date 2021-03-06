---
output: github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->






[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
                                                                                

# modelmanagr

## Abstract

The goal of `modelmanagr` is to create a framework for model management in R

Data Exploration and model building is not the end of the analytic process, in fact it is only the beginning. There is an immense need to make those models available for production use. This use raises some concerns around which model to use, model performance, and versioning of models over time.

After a predictive model is created it must then be productionalized. This is sometimes viewed, though oversimplified, as simply tying it to an api and throwing new data at it. While this may be true, there is a need to ensure that the model remains pertinent and performant into the future. The first step in addressing those needs is to store models in a repository where versions of the current model are saved as well as competing models. The next step is an ongoing monitoring process to ensure model performance. Finally, there is a parallel process to test current models versus competing models. Across all these steps there is a requirement that a single model can be flagged as active and that is the one used for ongoing predictions.

We will present a framework and a prototype package, `modelmanagr`, that demonstrates these steps.


## Installation

You can install the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("andrie/modelmanagr")
```
## Example

This is a basic example which shows you how to solve a common problem:


```r
## basic example code
```

