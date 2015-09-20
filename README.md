# Extensions - Fab Lab Sud31-Val d'Ariège edition

Theses extensions come from oni305 (https://hackaday.io/oni305) and are adapted to the our lab's equipment.

# Various Inkscape extensions

 - Raster 2 Laser GCode generator - Mr Beam (http://mr-beam.org/) + Fab Lab Sud31-Val d'Ariège (https://www.fablab-sud31.fr/) flavor

# Descriptions
- Raster 2 Laser GCode generator is an extension to generate Gcode for a laser cutter/engraver (or pen plotter), it can generate various type of outputs from a simple B&W (on/off) to a more detailed Grayscale (pwm)


# Installing:

Simply copy all the files in the folder "Extensions" of Inkscape

>Windows ) "C:\<...>\Inkscape\share\extensions"

>Linux ) "/usr/share/inkscape/extensions"

>Mac ) "/Applications/Inkscape.app/Contents/Resources/extensions"


for unix (& mac maybe) change the permission on the file:

>>chmod 755 for all the *.py files

>>chmod 644 for all the *.inx files



# Usage of "Raster 2 Laser GCode generator":

[Required file: png.py / raster2laser_gcode.inx / raster2laser_gcode.py]

- Step 1) Resize the inkscape document to match the dimension of your working area on the laser cutter/engraver (Shift+Ctrl+D)

- Step 2) Draw or import the image

- Step 3) To run the extension go to: Extension > 305 Engineering > Raster 2 Laser GCode generator

- Step 4) Play!


# Note
I have created all the file except for png.py , see that file for details on the license

##Laser power
With the laser-power is meant the power this actually drives the diode.
e.g. my laser doen't burn my wood ad power of 1, but starting at a power of 20, this ensures you can transpose the levels of grayscale to wood *given* (the levels of grayscale)  > laserpower_Max - laserpower-Min

future work may implement non-linear scaling ?
