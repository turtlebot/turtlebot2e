# Recommended Accessories

To make use of the TurtleBot2e it's important to have the ability to debug easily and quickly.
To that end we recommend the following accessories be on hand to connect to and debug a TurtleBot2e because it does not have an integrated display.

It is not necessary to have one set of accessories per robot.
It is recommended to have one set of 

## Keyboard + Mouse

<https://secure.logitech.com/en-us/product/wireless-touch-keyboard-k400r> 

The portable Logitech K400 keyboard is very versitile and offers both keyboard and mouse capabilities when mobile.
All drivers are built into the core kernel and the convenient off switch lets it go a long time between needing new batteries.

## Monitor

<https://www.adafruit.com/products/1033>

This monitor is relatively portable however still has enough resolution to support full width text.
If you are in a lab environment a desktop monitor with a moderately long HDMI cable will be much more convenient.
The monitors by default need external power.

It is expected in the future to use a 7" touch screen display and embed it into a modified top mounting plate to provide an integrated display.

## USB Hub

<http://www.newegg.com/Product/Product.aspx?Item=9SIA2BP0T23948>

Once you have a USB sensor, the Astra, and the Kobuki base the USB ports are full which does not leave space for anything else.
There are cheaper USB hubs available however not all hubs are capable of streaming the data from depth cameras.
Feel free to choose a different USB hub but make sure to test it before expecting to use it.
In development we have tested several lower cost hubs with little to no success.
The failures will usually cause unstable behavior of the usb drivers either in the kernel or user space.
