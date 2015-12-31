[![Build Status](https://travis-ci.org/rocker-org/rstudio-daily.svg)](https://travis-ci.org/rocker-org/rstudio-daily)


rocker/rstudio-daily
======================

- `rocker/rstudio-daily:latest` Provides the latest daily build of pre-release RStudio-server. The image builds off of `rocker/drd`, using development R (`RD`) as the R engine for RStudio. `rocker/drd` and this image are both rebuilt daily.

- `rocker/rstudio-daily:verse` (Dockerfile in `verse/`) adds the `rocker/hadleyverse` recipe (with occassional adjustment for development R) on top of the `rocker/rstudio-daily` image.

