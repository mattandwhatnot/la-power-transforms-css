# la-power-transforms-css
Line Awesome "Power Transform" like functionality using CSS 


## What is this?

Font Awesome 5 provides some really neat functionality they call Power Transforms.
Power Transforms allow you to shrink icons, rotate icons, and layer icons in endless ways.

The fa5-power-transforms-css project recreates some of the key Power Transform features in CSS.

This project is a variation for Icons8 Line Awesome. Focused on the specific feature of XY alignment when stacking.


## Which `data-la-transform` options are recreated?

`rotate-n`
- Rotates the icon by a given number of degrees.
- Supports whole numbers only, multiples of 5, -355 to 355.

`flip-h`, `flip-h`
- Flips an icon horizontally, vertically, or both.

`shrink-n`, `grow-n`
- Reduces the size, or increases the size.
- Supports whole numbers from 1 to 16.

### `.la-layer` only

Line Awesome uses the `la-stack` container. To get these features, use `la-layers`.

`up-n`, `down-n`, `left-n`, `right-n`
- Supports whole numbers from 1 to 8.

#### For simplicity and scope `mask` and `glow` has been removed

