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

### Helpful Hints
Here are some commands that will help you build, install, and take a screenshot of
your watchface if you want to publish it.

```
pebble build
```
```
pebble install --phone YOUR_PHONES_IP_ADDRESS
```
```
pebble screenshot --phone YOUR_PHONES_IP_ADDRESS
```

If you want to install the watchface on your phone/watch, you will need to make sure
the pebble phone app is in dev mode. Also make sure that you are in the app and that
your phone is not sleeping or else it will fail to connect and not install. 

You can find your phone's IP address in the developer tab of the pebble app.
