# investr: Inverse Estimation in R

Inverse estimation, also referred to as the calibration problem, is a classical and well-known problem in regression. In simple terms, it involves the use of an observed value of the response (or specified value of the mean response) to make inference on the corresponding unknown value of the explanatory variable. 

A detailed introduction to investr has been published in The R Journal: "investr: An R Package for Inverse Estimation", http://journal.r-project.org/archive/2014-1/greenwell-kabban.pdf. You can track development at https://github.com/w108bmg/investr. To report bugs or issues, contact the main author directly or submit them to https://github.com/w108bmg/investr/issues. 

## Installation
The package is currently listed on CRAN and can easily be installed:
```S
  ## Install from CRAN
  install.packages("investr", dep = TRUE)
```
The package is also part of the [ChemPhys task view](http://cran.r-project.org/web/views/ChemPhys.html) --- a collection of R packages useful for analyzing data from chemistry and physics experiments. These packages can all be installed at once (including `investr`) using the `ctv` package (Zeileis, 2005):
```S
  ## Install the ChemPhys task view
  install.packages("ctv")
  ctv::install.views("ChemPhys")
```


