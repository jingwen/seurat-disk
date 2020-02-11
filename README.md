
<!-- README.md is generated from README.Rmd. Please edit that file -->

# SeuratDisk v0.0.0.9000

<!-- badges: start -->

![CRAN/METACRAN](https://img.shields.io/cran/v/SeuratDisk)
<!-- badges: end -->

Interfaces for HDF5-based Single Cell File Formats

## Installation

SeuratDisk is not currently available on CRAN. You can install it from
[GitHub](https://github.com/mojaveazure/seurat-disk) with:

``` r
if (!requireNamespace("remotes", quietly = TRUE)) {
  install.packages("remotes")
}
remotes::install_github("mojaveazure/seurat-disk")
```

## Dependencies

SeuratDisk depends on the following
packages:

| Package |                   CRAN Webpage                    |                    Source                     |                   Website                   |
| :-----: | :-----------------------------------------------: | :-------------------------------------------: | :-----------------------------------------: |
|  hdf5r  | [CRAN](https://cran.r-project.org/package=hdf5r)  |  [GitHub](https://github.com/hhoeflin/hdf5r)  | [Website](https://hhoeflin.github.io/hdf5r) |
| methods |                         –                         |                       –                       |                      –                      |
|   R6    |   [CRAN](https://cran.r-project.org/package=R6)   |    [GitHub](https://github.com/r-lib/R6/)     |       [Website](https://r6.r-lib.org)       |
|  rlang  | [CRAN](https://cran.r-project.org/package=rlang)  |   [GitHub](https://github.com/r-lib/rlang)    |      [Website](http://rlang.r-lib.org)      |
| Seurat  | [CRAN](https://cran.r-project.org/package=Seurat) | [GitHub](https://github.com/satijalab/seurat) | [Website](http://www.satijalab.org/seurat)  |
|  tools  |                         –                         |                       –                       |                      –                      |
