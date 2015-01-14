nxc-tetris
==========

The classic game of Tetris, now on your NXT!

Compile with the NXC compiler.

*Requires enchanced NBC/NXC firmware.*

**Note:** You must aquire the `#include` files. You can find them in the [nxc-modules repository](https://github.com/ArtskydJ/nxc-modules).

#Features

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
	- -Allows only 1 floor kick per piece.- *Deleted* (Don't like.)
	- Always allows the `I` piece to wall kick.
	- Allows the `I` piece to floor kick even when it's not touching the ground
- Adheres to all of the [SRS guidelines](http://tetris.wikia.com/wiki/SRS), and some of the [ARS guidelines](http://tetris.wikia.com/wiki/ARS).

#Known Issues

- Crashes a few min into the game
	- Not due to memory
- Can't see piece well while soft dropping

#To Do

- Split everything into separate files!
- Change the coding style. I wrote it over 2 years ago and it looks ugly now. :)

#License

[VOL](http://veryopenlicense.com)
