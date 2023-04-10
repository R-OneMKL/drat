# drat - R-OneMKL R package repository

We are using the [drat](https://cran.r-project.org/package=drat) R package to set up the infrastructure for a mini R-OneMKL  R package repository.

### Usage

#### Package Users: Installation of R-OneMKL R packages

You can install packages from the R-OneMKL repository directly with `install.packages()`.

```r
install.packages(c("oneMKL", "oneMKLUtil"), repos="https://R-OneMKL.github.io/drat")
```

The other way to use this drat repository is to leverage `drat` package:

```r
install.packages("drat")
drat::addRepo("R-OneMKL") # append R-OneMKL repository to repo list
install.packages(c("oneMKL", "oneMKLUtil"))
```
