
## Learning {infer}

This repository contains source code for a {learnr} tutorial for the R
package [{infer}](https://github.com/tidymodels/infer)\!

To run the tutorial, you’ll need to have the {learnr} and {gradethis}
packages installed, in addition to the {infer} package itself. You can
install those packages with the following code:

``` r
# install infer and learnr from CRAN
install.packages("infer")
install.packages("learnr")

# gradethis isn't on CRAN, so install it
# using the devtools package!
# install.packages("devtools")
devtools::install_github("rstudio-education/gradethis")
```

Once you have these packages installed, you should be able to run the
tutorial by knitting the `infer.Rmd` file. :grinning:

Once the tutorial is finished, it will be hosted online so that no
package installation is required\!
