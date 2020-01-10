nxc-tetris
==========

The classic game of Tetris, now on your NXT!

Compile with the NXC compiler.

*Requires enchanced NBC/NXC firmware.*

**Note:** You must acquire the `#include` files. You can find them in the [nxc-modules repository](https://github.com/ArtskydJ/nxc-modules).

## Features

- Official Process Order:
	- Rotation
	- Move
	- Drop
	- Gravity
- Included capabilities:
	- Soft Drop
	- Hard Drop
	- Clockwise Rotation
	- Right Side Bias
	- Delayed Auto Shift
	- Wall kicks
- Almost official "kicking"
	- Officially only allows 1 floor kick per piece. *Disabled*
	- Always allows the `I` piece to wall kick.
	- Allows the `I` piece to floor kick even when it's not touching the ground
- Adheres to all of the [SRS guidelines](http://tetris.wikia.com/wiki/SRS), and some of the [ARS guidelines](http://tetris.wikia.com/wiki/ARS).

## Known Issues

- Crashes a few min into the game (Not due to memory)... *I haven't been able to replicate this recently.*
- Can't see piece well while soft dropping
- The game does not speed up
- Should use the ["Random Generator"](https://tetris.fandom.com/wiki/Random_Generator) (grab-bag) approach
- The keyboard for the high-score screen isn't showing the letters
- Button presses are not always caught
- Move RotatedNumbers.nxc into nxc-modules repo at some point?

## To Do

- Split everything into separate files!
- Change the coding style. I wrote it over 2 years ago and it looks ugly now. :)

## License

[VOL](http://veryopenlicense.com)
