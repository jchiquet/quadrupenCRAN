
Minor release to fix deprecated way of setting an error streamin (Rcpp)Armardillo

* tested remotely with github action (macOS, ubuntu, Windows release, unbuntu devel)
* tested remotely with win-builder (release, devel, oldrel)
* tested remotely with R-hub (Windows Server 2022, Fedora Linux, R-devel, clang, gfortran, Ubuntu Linux 20.04.1 LTS, R-release, GCC)
* tested locally on Ubuntu 22.04, R 4.2.2

── R CMD check results ─────────────────────────────────────────── quadrupen 0.2-10 ────
Duration: 1m 48.3s

❯ checking installed package size ... NOTE
    installed size is  5.7Mb
    sub-directories of 1Mb or more:
      libs   5.6Mb

0 errors ✔ | 0 warnings ✔ | 1 note ✖

R CMD check succeeded