
This submission corrects the following request from CRAN maintainers 

* Suppress warning in C++ due to comparison between signed and unsigne integer

* tested locally on Ubuntu 20.04, R 4.0.2

── R CMD check results ──────────────────────────────────── quadrupen 0.2-8 ────
Duration: 1m 9s

> checking installed package size ... NOTE
    installed size is 14.5Mb
    sub-directories of 1Mb or more:
      libs  14.0Mb

0 errors ✓ | 0 warnings ✓ | 1 note x

R CMD check succeeded

* tested remotely with github action (macOS, ubuntu, Windows release, unbuntu devel)

* tested remotely with winbuilder (devel)

* tested remotely with R-hub (release Debian, Ubuntu, Fedora)
