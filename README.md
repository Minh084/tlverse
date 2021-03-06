<!-- README.md is generated from README.Rmd. Please edit that file -->
tlverse
=======

`tlverse` is an umbrella package for targeted learning in R.

`library(tlverse)` loads the following core packages:

-   [sl3](https://jeremyrcoyle.github.io/sl3/) for SuperLearning
-   [tmle3](https://jeremyrcoyle.github.io/tmle3/) for TMLE (Targeted Minimum Loss-based Estimation)

as well as the following helper packages:

-   [delayed](https://github.com/jeremyrcoyle/delayed) for parallelizing dependent tasks
-   [origami](https://github.com/jeremyrcoyle/origami) for cross-validation

and packages for individual tmle3 parameters:

*coming soon*

Installation
------------

Some of these packages are not yet on CRAN, so for now the only option is to install directly via github using devtools:

    devtools::install_github("jeremyrcoyle/tlverse")
