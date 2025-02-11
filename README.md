R Package GWASpoly
================

This package was designed for genome-wide association studies in
autopolyploids but also works for diploids. A [vignette is
available](https://jendelman.github.io/GWASpoly/GWASpoly.html) to
illustrate the basic workflow using the potato dataset that comes with
the package. More detailed information is available in the [package
reference
manual](https://jendelman.github.io/GWASpoly/GWASpoly_manual.pdf).

If you use the package in a publication, please cite Rosyara et
al. (2016) Plant Genome 9 <doi:10.3835/plantgenome2015.08.0073>

The original development of the package was supported by the USDA NIFA
SCRI (Award No. 2011-51181-30629) and Hatch (Accession No. 1002731)
programs. Beginning Fall 2020, new features are being added as part of
the SCRI Project “Tools for Genomics-Assisted Breeding in Polyploids”
(Award No. 2020-51181-32156).

To install and load the package:

``` r
install.packages("devtools")
devtools::install_github("jendelman/GWASpoly", build_vignettes=FALSE)
library(GWASpoly)
```
