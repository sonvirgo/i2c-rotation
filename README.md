# i2c-rotation
THE MOTIVATION 

Touchscreen work beutifully on traditional OSs and now macOS. macOS support display mode of 90, 180, 270 degrees
https://youtu.be/JEVYvdY95l0

WHAT HAVE KNOWN SO FAR

Open sorce kernel driver work out of box with i2c auto-rotation sensor since Ubuntu Gnome 16.04, Gnome 3.18, kernel 4.4.0-31 

https://youtu.be/pgj5JuTJrzw

Alexandre Daoud has successfully made kext for some touch device, so rotation sensor is easier to achieve  
https://github.com/alexandred/VoodooI2C

Similar project has relesaed their solution
https://github.com/martin-ueding/thinkpad-scripts

https://aaporantalainen.wordpress.com/2011/03/08/kayttojarjestelma-ilman-seinia/

https://github.com/changty/lenovo-rotate

Initial people interested:

sonvirgo is doing testing on real device and doing intergrating fb-rotate script to macOS

cydia2020 is doing IoKit portion of the kext
https://youtu.be/oC9C5TAV_5c

wafflejock is linux side advisor 

All kind of joinning are welcome!

TO DO LIST

Grab the source code from linux source, may be kernel module

Port the source to macOS and chainload in macOS kext (kernel space driver)

Interprete hardware event to fb-rotation script

Tesing

Done

