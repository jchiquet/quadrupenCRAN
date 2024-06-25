
Minor release to fix error with version 14 of (Rcpp)Armardillo 

* tested remotely with github action (macOS, ubuntu devel, old, release, Windows release)
* tested remotely with win-builder (release, devel, oldrel)
* tested locally on Ubuntu 22.04, R 4.4.1

   Status: 1 NOTE

── R CMD check results ────────────────────────── quadrupen 0.2-12 ────
Duration: 2m 30.2s

❯ checking installed package size ... NOTE
    installed size is  6.1Mb
    sub-directories of 1Mb or more:
      libs   5.6Mb

0 errors ✔ | 0 warnings ✔ | 1 note ✖

R CMD check succeeded
