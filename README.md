[PLINK2R](https://github.com/oujenhsiang/PLINK2R) is an easy-to-use R package that can read [PLINK](https://www.cog-genomics.org/plink/1.9) binary format data to R. Four packages are used (you don't need to install them manually):

- `data.table`
- `tibble`
- `dplyr`
- `genio`

## Installation

This package is not published on CRAN, and you will need to install it from GitHub.

```R
#install.packages("devtools")
devtools::install_github("oujenhsiang/PLINK2R")
```

## Usage

```R
library(PLINK2R)
readPLINK(prefix)
```

- `prefix`: The directory and prefix of all binary files. Three files need to be placed at the same folder which included:
  - prefix.bed
  - prefix.bim
  - prefix.fam
