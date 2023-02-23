
# manyigos <img src="man/figures/manyigoslogo.png" align="right" width="220"/>

<!-- badges: start -->

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
![GitHub release (latest by
date)](https://img.shields.io/github/v/release/globalgov/manyhealth)
![GitHub Release
Date](https://img.shields.io/github/release-date/globalgov/manyhealth)
<!-- badges: end -->

`manyigos` is a data package within the [many universe of
packages](https://github.com/globalgov). It contains an ensemble of
datasets currently available on intergovernmental organizations in the
world, including information on their beginning and, where applicable,
end dates, state members, and aspects of institutional design. The
package is geared towards global governance research, but can also be
used by anyone interested in international organizations across time.

Please also check out
[`{manydata}`](https://github.com/globalgov/manydata) for more
information about the other packages and tools to handle data from the
many universe of packages.

## How to install:

We’ve made it easier than ever to install and start analysing global
governance data in R. Simply install the core package,
[manydata](https://github.com/globalgov/manydata), as outlined below, to
discover, install, and update various packages from the many packages
universe.

``` r
manydata::get_packages() # this prints a list of the publicly available data packages currently available
```

    ## # A tibble: 7 × 6
    ##   Name        Repository            Installed Latest Updated    Description     
    ##   <chr>       <chr>                 <chr>     <chr>  <date>     <chr>           
    ## 1 manydata    globalgov/manydata    0.8.2     0.8.2  2022-11-17 An R portal for…
    ## 2 manyenviron globalgov/manyenviron 0.2.1     0.2.2  2022-10-18 Ensembled data …
    ## 3 manyhealth  globalgov/manyhealth  0.2.0     0.2.0  2023-02-14 Ensembled data …
    ## 4 manypkgs    globalgov/manypkgs    0.2.3     0.2.2  2022-07-21 Support for cre…
    ## 5 manystates  globalgov/manystates  0.1.1     0.2.0  2022-10-17 Ensembled data …
    ## 6 manytrade   globalgov/manytrade   0.2.0     0.2.0  2022-10-17 Ensembled data …
    ## 7 messydates  globalgov/messydates  0.3.5     0.3.5  2023-01-20 An R package fo…

``` r
#manydata::get_packages("manyigos") # this downloads and installs the named package
```

## Data included

Once you have installed `{manydata}`, you can see the different
databases and datasets included in the `{manyigos}` package using the
following function.

``` r
# manydata::data_contrast("manyigos")
```

Working with ensembles of related data has many advantages for robust
analysis. Just take a look at our vignettes
[here](https://globalgov.github.io/manydata/articles/user.html).

## The many packages universe

The [many universe of packages](https://github.com/globalgov/manydata)
is aimed at collecting, connecting and correcting network data across
issue-domains of global governance.

While some of our packages can and do include novel data, much of what
they offer involves standing on the shoulders of giants. Our packages
endeavour to be as transparent as possible about where data comes from,
how it has been coded and/or relabeled, and who has done the work. As
such, we make it easy to cite both the particular datasets you use by
listing their original references with the first function below, as well
as the package providers for their work assembling the data using the
second function.

``` r
# Citing the original data
# manydata::data_source("manyigos")
# Citing the package
citation("manyigos")
```

    ## 
    ## To cite in publications use:
    ## 
    ##   Hollway, James.manyigos.2022
    ## 
    ## A BibTeX entry for LaTeX users is
    ## 
    ##   @Manual{,
    ##     title = {manyigos},
    ##     author = {{Hollway} and {James}},
    ##     year = {2022},
    ##     note = {For more information on the manyverse: https://github.com/globalgov/manydata},
    ##   }

## Contributing

[manydata](https://github.com/globalgov/manydata) and
[manypkgs](https://github.com/globalgov/manypkgs) also makes it easy to
contribute in lots of different ways.

If you have already developed a dataset salient to this package, please
reach out by flagging it as an
[issue](https://github.com/globalgov/manyigos/issues) for us, or by
forking, further developing the package yourself, and opening a [pull
request](https://github.com/globalgov/manyigos/pulls) so that your data
can easily be integrated into the package.

If you have collected or developed other data that may not thematically
fit in this package, but could be useful within the many packages
universe, [manypkgs](https://github.com/globalgov/manypkgs) includes a
number of functions that make it easy to create a new package and
populate with global governance data.

If you have any further ideas about how this package, or the various
other ‘many packages’, might better facilitate your empirical analysis,
we’d be very happy to hear from you.