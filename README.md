findPackage
==========

The `findPackage` package helps you find the sos package.

## Installation

Currently there isn't a release on [CRAN](http://cran.r-project.org/).

You can, however, download the [zip ball](https://github.com/Dasonk/findPackage/zipball/master) or [tar ball](https://github.com/Dasonk/findPackage/tarball/master), decompress and run `R CMD INSTALL` on it, or use the **devtools** package to install the development version:

```r
## Make sure your current packages are up to date
update.packages()
## devtools is required
library(devtools)
install_github("findPackage", "Dasonk")
```