# SVG to D3.js Compiler

This is a very simple SVG to D3.js compiler. It was written with the intention of allowing me to 
quickly translate textures generated in Inkscape to Javascript. This translation isn't a particularly good 
one. UUID like variables are used to get variable names and there is no concept of .enter() or of .remove().
However, it does a good job translating a multitude of nested attributes. So it can end up saving a lot of time.

1. Load page and hit Ctrl-V to paste into the SVG text area.
2. Press tab.
3. Press Ctrl-A to select all of the D3.js text area contents.
4. Press Ctrl-C to copy all the contents.

Given an existing 500 line SVG file, already in the paste buffer, it should be possible to replace your 
clipboard with a d3.js equivalent within two seconds of loading the page.