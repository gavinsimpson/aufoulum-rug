# Introduction to R

## 2021-11-10

## Packages

We need the following packages

```r
# packages needed
pkgs <- c("ggplot2", "dplyr", "palmerpenguins")

# install needed packages
install.packages(pkgs, Ncpus = 2)
```

then load the packages to confirm

´´´r
vapply(pkgs, library, logical(1L), logical.return = TRUE, character.only = TRUE)
```

