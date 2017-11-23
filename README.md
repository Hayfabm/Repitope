Repitope: Epitope prediction via repertoire-wide TCR-peptide contact profiles
===============================================

The 'Repitope' package provides some easy-to-use functions for conducting epitope prediction analysis via repertoire-wide TCR-peptide contact profiles.
Note: Repitope is currently under construction.

Installation
------------------------

-   Install the latest version from [GitHub](https://github.com/masato-ogishi/Repitope) as follows:

``` r
if(!require(devtools)) install.packages("devtools")
devtools::install_github("masato-ogishi/Repitope")

# Alternatively, please download this repository as a Zip file, unzip it to the directory you want, and run the following command.
devtools::install_local("path/to/the/unzipped/folder")
```

-   You might be prompted to install some packages before installling Repitope. Follow the message(s).

Loading
------------------

``` r
# Loading the Repitope package
library(Repitope)
```

Usage
-----------------------------------
``` r
# Setting up the working environment
set.seed(12345)
library(tidyverse)
```

Reference
------------------------

Ogishi, M and Yotsuyanagi, H. (2017) "Epitope prediction through quantitative modeling of repertoire-wide epitope-TCR interactions in human." (Manuscript in preparation)
