
Resubmission

The initial submission corrects an error that causes the package to be archived

  _Suppress warning in C++ due to comparison between signed and unsigne integer_

The resubmission corrects the following requests from CRAN maintainers

- formatting in DESCRIPTION (reference/citation)
- removing dontrun in examples, add donttest only for examples > 5s

Additional changes:
  * change address of maintainer (julien.chiquet@inra.fr -> julien.chiquet@inrae.fr)  
  * change the default number of cores to 2

* tested remotely with github action (macOS, ubuntu, Windows release, unbuntu devel)
* tested remotely with win-builder (devel)
* tested remotely with R-hub (release Ubuntu, Fedora)
* tested locally on Ubuntu 20.04, R 4.0.2

── R CMD check results ──────────────────────────────────── quadrupen 0.2-8 ────
Duration: 1m 9s

> checking installed package size ... NOTE
    installed size is 14.5Mb
    sub-directories of 1Mb or more:
      libs  14.0Mb

0 errors ✓ | 0 warnings ✓ | 1 note x

R CMD check succeeded

