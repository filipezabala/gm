# gm 2.0.0

## Features

* Add many new components (#11 #4).
* Represent music with data frames.
* Refactor code. Now it's more developer-friendly.
* Reduce package dependencies.

## Breaking Changes

* Deprecate argument `tie` of `Line()`. Use `Tie()` instead.
* Deprecate argument `unit` of `Tempo()`. Use `marking` instead.
* Change arguments of `export()`.
* Remove `tuplet()` and `Tupler()`. Use argument `durations` of `Line()` instead.


# gm 1.0.4

* Recognize Shiny apps.


# gm 1.0.3

* Change default score margin to 0.
* Add "MuseScore Command Line Options" in `vignette("gm")`.
* Improve `show()` and `export()` to accept MuseScore command line options
(#10).


# gm 1.0.2

* Fix bug of not showing scores when knit to PDF or Word (#9).
* Make filling rest notes after Lines invisible.
* Add short introduction in Chinese.
* Add "Comparison" section in `vignette("gm")`.


# gm 1.0.1

* Improve `Line()` to accept non-logical `NA` as pitch.
* Improve error message for `pitches` in `Line()`. 
* Fix bug of incorrect default MuseScore path for Windows (#1).
* Fix bug in error message for `durations` in `Line()`.
* Add acknowledgement.
