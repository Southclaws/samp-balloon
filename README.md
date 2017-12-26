# balloon.inc

Extremely simple balloon library. Create balloons that have start and end coordinates, players can ride them.

## Installation

Simply install to your project:

```bash
sampctl package install Southclaws/samp-balloon
```

Include in your code and begin using the library:

```pawn
#include <balloon>
```

## Usage

`CreateBalloon` to create a balloon with a given start and end coordinates/rotation.

When a player jumps in and hits the button, the ballon simply flies to the other location. Works both ways.

The rest of the API is pretty standard and simple, just read the code.

## Testing

To test, simply run the package:

```bash
sampctl package run
```

And connect to `localhost:7777` to test.
