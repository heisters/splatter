Summary
=======

This is a static, one-page app that mimicks splashing paint on canvas.

[See it in action.](http://heisters.github.io/splatter)

Configuration
=============

The application is configured by passing URL parameters.

* `uid`: a user ID, passed to Google Analytics for user tracking.
* `refreshAfterSeconds`: refresh the page after the given number of
  seconds of inactivity. Defaults to not refreshing.
* `sensitivity`: a multiplier to be applied to velocity calculations. On
  retina displays like newer iPads, `2.0` is a reasonable setting.
  Defaults to the value of `window.devicePixelRatio`.
* `kiosk`: if set, all outgoing links will be disabled. Setting this
  flag to anything, including `false` or `0`, will enable it.
* `palette`: a string identifying the color palette to use. Valid values
  are `convergence` (based on Jackson Pollock's piece _Convergence_),
  `bright`, `dark`, and `redwhiteblack`. Defaults to `convergence`.
