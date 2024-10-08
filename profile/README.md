A set of solutions to geodesy problems in various programming languages; in
Haskell, F#, Unison, Koka, Lean, and Rust.

## The Direct or Forward Problem

  * {x} The departure point on the ellipsoid.
  * {α₁} The azimuth from the departure point.
  * {s} The distance to the arrival point.
  
Given the above inputs, find:
  * {y} The arrival point.
  * {α₂} The azimuth at the arrival point.


## The Inverse or Reverse Problem[^1]

  * {x} The departure point.
  * {y} The arrival point.

Given the above inputs, find:
  
  * {s} The distance between departure and arrival points.
  * {α₁} The azimuth at the departure point.
  * {α₂} The azimuth at the arrival point.

[^1]: Sometimes called the indirect problem.