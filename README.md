![GIF Preview](frag.gif)

Author: Mun Hon Cheong (mhch295@cse.unsw.edu.au)

Program: Frag - a FPS i put together using Haskell and with Yampa

Year: 2005, 2007-8

License: GPL

Usage: $ frag leveleg

'leveleg' can be an arbitrary Quake III Arena level; a default level is provided in this package, and is installed in 'share/frag-1.1', wherever that is. For example, if it's installed into ~/bin, and frag occupies ~/bin/frag, a successful invocation might be 'frag ../share/frag-1.1/leveleg'.

Requirements: A graphics card with support for multitexturing and vertex arrays

Building:
    ghc --make -O2 -fglasgow-exts main.hs
or
    runhaskell Setup configure --user --prefix=/home/foo
    runhaskell Setup build
    runhaskell Setup install

Controls: mouse moves around the view, 'w'\'a'\'s'\'d' to move and strafe, 'e to jump, 'z' and 'x' to lock and unlock the mouse, left click to fire.

cheers,
Mun


