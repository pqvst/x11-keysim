x11-keysim
==========

Utility program to simulate an arbitrary Unicode character using X11.

Install
-------

You will need the X11 (libx11-dev) and XTest (libxtst-dev) dev libraries.

Compile the cpp file. Make sure to link with the X11 and Xtst libraries.

See ./test

Usage
-----

You should pass the unicode character code (in hex). 

Optionally tell the program to sleep n seconds before it simulates the key (useful for testing).

    ./keysim 0x00d6 [--sleep n]
    
Credits
-------

http://www.cl.cam.ac.uk/~mgk25/ucs/keysyms.txt
