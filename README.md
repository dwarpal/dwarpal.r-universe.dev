# dwarpal R-universe

Registry for [dwarpal.r-universe.dev](https://dwarpal.r-universe.dev), which
builds the R packages listed in [`packages.json`](packages.json) from their
GitHub repositories into binaries for Windows, macOS and Linux.

```r
install.packages("credgate",
  repos = c("https://dwarpal.r-universe.dev", "https://cloud.r-project.org"))
```

This installs the latest development version from `main`. The released
version is on CRAN: `install.packages("credgate")`.
