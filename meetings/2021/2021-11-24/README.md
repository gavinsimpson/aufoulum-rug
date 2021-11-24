# Reading data into R

## 2021-11-24

## Packages

We need the following packages

```r
# packages needed
pkgs <- c("readr", "readxl")

# install needed packages
install.packages(pkgs, Ncpus = 2)
```

then load the packages to confirm

´´´r
vapply(pkgs, library, logical(1L), logical.return = TRUE, character.only = TRUE)
```

