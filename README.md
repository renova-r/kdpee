# kdpee

Fast multidimensional entropy estimation by k-d partitioning.

Compatibility updates by Renova.

Version 1.0.0.9001 replaces the deprecated `Calloc` and `Free` memory macros in `src/kdpee.c` with `R_Calloc` and `R_Free`. No R function was changed.

## Install

```r
install.packages("kdpee", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/kdpee@renova-1.0.0.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

kdpee is by Olaf Mersmann (maintainer) and Dan Stowell; copyright holders include Queen Mary University of London. The original CRAN package is at <https://CRAN.R-project.org/package=kdpee>. The method is described in Stowell and Plumbley (2009), see `citation("kdpee")`. License: GPL (>= 3); see [COPYING](COPYING).
