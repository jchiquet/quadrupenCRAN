
This submission corrects the following request from CRAN maintainers 

  _Suppress warning in C++ due to comparison between signed and unsigne integer_
  
* change addresse of maintainer (julien.chiquet@inra.fr -> julien.chiquet@inrae.fr)  

* tested remotely with github action (macOS, ubuntu, Windows release, unbuntu devel)
* tested remotely with winbuilder (devel)
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

