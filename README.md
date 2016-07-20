# watchface_1
A pretty pebble watchface. It's dainty and mysterious, hiding the time so that 
only you will be able to read it at a glance.

###  Documentation
This watchface is written in C using the Pebble SDK. The basic watchface setup 
is minimal and it's easy to add images and custom fonts.
The src directory contains the C code, the resources directory contains the 
uploaded image and the font. Note that the images must be in .png format and fonts 
must be a .ttf format.

Resources must be added to the package.json file in the "resources"/"media" block. 
