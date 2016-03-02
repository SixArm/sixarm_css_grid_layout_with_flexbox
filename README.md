# SixArm.com » CSS » <br> Grid layout with flexbox

To accomplish a CSS grid layout with flexbox,
we use the excellent work published by Philip Walton,
in the open source "Solved By Flexbox" repository:
https://github.com/philipwalton/solved-by-flexbox/blob/master/demos/grids.md

Files:

  * [demo.css](demo.css)
  * [demo.html](demo.html)


## Changes ##

We have edited the CSS code with the goal of making it easier for beginners:

 * Added comments, examples, and annotations
 * Included the basic grid and grid cell, and omitted all other components.
 * Included the basic media queries, and omitted all other media queries.


## Naming Conventions ##

The CSS code uses the naming conventions of SuitCSS:

  * .ComponentName
  * .ComponentName-partName


## Media queries ##

The layout uses media queries to enable responsive pages:

 * A small screen shows each grid cell as a row.
 * A large screen shows each grid cell as a column.
