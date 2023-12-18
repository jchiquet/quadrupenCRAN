
Minor release to fix deprecated way of setting error in (Rcpp)Armardillo and correction in documentation

* tested remotely with github action (macOS, ubuntu devel, old, release, Windows release)
* tested remotely with win-builder (release, devel, oldrel)
* tested remotely with R-hub (Windows Server 2022, Fedora Linux, R-devel, clang, gfortran)
* tested locally on Ubuntu 22.04, R 4.3.2

   Status: OK
   
── R CMD check results ──────────────────────── quadrupen 0.2-11 ────
Duration: 2m 43.7s

❯ checking installed package size ... NOTE
    installed size is 10.6Mb
    sub-directories of 1Mb or more:
      libs  10.2Mb

0 errors ✔ | 0 warnings ✔ | 1 note ✖
