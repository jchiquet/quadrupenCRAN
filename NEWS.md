# quadrupen 0.2-12

  - Minor fix in penscale format (colvec) w.r.t armadillo 14

# quadrupen 0.2-11

  - Minor fix in documentation an error handling in armadillo

# quadrupen 0.2-10

  - Fix deprecated way of setting an output or error stream (Dirk E. PR)

# quadrupen 0.2-9

  - Adaptation due to new Matrix version 1.4-2
  - fix for HTML5 in documentation

# quadrupen 0.2-8	(2020-11-04)
    Minor:
    +   Avoid warning in C++ to pass CRAN checks, thanks to a PR of Dirk Eddelbuettel <edd@debian.org>
    +   Minors changes in examples, default mc.cores to 2

# quadrupen 0.2-7	(2019-08-27)
    Minor:
    +   change sort(, 1) to sort(, "descend") in C++ code to avoid warnings during checks

# quadrupen 0.2-6	(2018-04-30)
    Minor:
    +   change & to && in C++ code to avoid warnings during checks

# quadrupen 0.2-5	(2017-03-06)
    Minor:
    +   change "package = " to "PACKAGE = "

# quadrupen 0.2-4	(2014-01-16)
    Minor:
    +   memory leak corrected (sp_mat declaration)
    +   linking to Rcpp/RcppArmadillo headers (requires R 3.0-2)

# quadrupen 0.2-3	(2013-08-26)
    +   added back the 'normalize' parameter
    +   standardization is performed within the C++ code
    +   use of sparse conversion from Matrix to Armadillo
    +   corrected bug with the 'intercept' and 'residuals' components of the quadrupen class
    +   added more tests in the inst directory
    +   correction in the documentation
    +   added r.squared to the quadrupen class

# quadrupen 0.2-2	(2013-04-08)
    +   minor fix to comply with recent ggplot2 updates.

# quadrupen 0.2-1	(2013-02-27)
    +   minor fix to pass CRAN check on Windows operating systems.

# quadrupen 0.2-0	(2013-02-26)
    Major:
    +	added bounded regression (regression penalized by infinity norm + structered l2 norm)
    +   added corresponding functionalies for cross-validation and stability path
    Minor:
    +   corrected wrong annotations of the stability path (PFER)
    +   handled normalization internally ('normalize' is no longer a parameter)
    +   more simple internal handling of penscales and correction of the rescaling of the intercept
    +   better use of multicore features
    +   handled runtime error exception in RcppArmadillo when the system is singular (end of the solution path)
        A consequence is quadrupen is less likely to crash due to user's "bad" parametrization
    +   simplification of the C++ code, bugs corrected, probably new ones added :-'(
    +   added 'examples' and 'tests' directories

# quadrupen 0.1-0	(2012-10-09)
    +	first build: structured elastic-net with (weighted) quadratic loss, cross-validation and stability selection methods.
