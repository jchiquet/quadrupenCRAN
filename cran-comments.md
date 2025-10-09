Minor release to fix errors with version 15 of (Rcpp)Armardillo 
Also update use of ggplot2 deprecated function

* tested remotely with github action (macOS, ubuntu devel, old, release, Windows release)
* tested remotely with win-builder (4.5.1, 4.4.3, release, devel, oldrel)
* tested locally on Ubuntu 24.04, R 4.5.1

Status: 1 NOTE (due to compiler option on my local Ubuntu)

── R CMD check results ───────────────────────────────────────────────────────────────── quadrupen 0.2-13 ────
Duration: 2m 4.1s

❯ checking compilation flags used ... NOTE
  Compilation used the following non-portable flag(s):
    ‘-mno-omit-leaf-frame-pointer’

0 errors ✔ | 0 warnings ✔ | 1 note ✖

R CMD check succeeded

