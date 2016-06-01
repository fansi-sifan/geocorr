
<!-- README.md is generated from README.Rmd. Please edit that file -->
About
=====

`geocorr` is an R data package for a set of geographic crosswalk files generated from the Missouri Census Data Center's [**Geo**graphic **Corr**espondence Engine: `MABLE/Geocorr14`](http://mcdc.missouri.edu/websas/geocorr14.html).

So far `geocorr` has four datasets:

-   `geocorr::county2010_to_puma2000`: County10-PUMA00 Crosswalk File
-   `geocorr::county2010_to_puma2012`: County10-PUMA12 Crosswalk File
-   `geocorr::county2014_to_puma2000`: County14-PUMA00 Crosswalk File
-   `geocorr::county2014_to_puma2012`: County14-PUMA12 Crosswalk File

The raw csv files, generated directly from [`MABLE/Geocorr14`](http://mcdc.missouri.edu/websas/geocorr14.html), can be found in the [`\data-raw\` folder](https://github.com/jjchern/geocorr/tree/master/data-raw).

Installation
============

``` r
# install.packages("devtools")
devtools::install_github("jjchern/geocorr")
```

Reference
=========

-   [IPUMA: Description of PUMA](https://usa.ipums.org/usa-action/variables/PUMA)
-   [PSC: Creating County-Level Statistics from Public Use Microdata Areas (PUMAS)](http://www.psc.isr.umich.edu/dis/census/Features/puma2cnty/)
