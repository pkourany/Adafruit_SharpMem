Adafruit_SharpMem
=================

Adafruit Sharp Memory Display Library adapted for Spark

Pin setup for Spark and 96x96 Sharp Memory Display

To display custom bitmap on a Sharp Memory make the .png 96px x 96px in an image editor program. Once the image is the correct size go to http://www.digole.com/tools/PicturetoC_Hex_converter.php and convert image to Hex code ie. 0x00...

Once you have the Hex code paste it over the old hex code and you should be all good!


Spark         | Sharp
------------- | -------------
3.3           | 3.3
GND           | GND
A3            | CLK
A5            | DI
A1            | CS

![Spark and Sharp Memory 96x96](https://raw.githubusercontent.com/dplumly/Dustins-Words/gh-pages/readme_img/Dustins%20Words%20SharpMem.jpg)

