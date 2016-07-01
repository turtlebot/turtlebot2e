# Hardware Instructions

To build a TurtleBot2e you will need the following parts. 

## Parts List

* TurtleBot2 Core Kit $1049.00 <http://www.turtlebot.com/distributors/>
 * Kobuki w/ charger
 * Plates
 * With astra mount
*   Orbbec Astra <https://orbbec3d.com/product-astra/> $149.99
*   DragonBoard 401c <https://www.96boards.org/products/ce/dragonboard410c/> $75
*   DragonBoard Heatsink Kit <https://www.element14.com/community/community/designcenter/single-board-computers/blog/2016/02/01/cooling-the-dragonboard-410c-and-ifc6410p> ~$15
*   DragonBoard 410c 12V TurtleBot power cord (12V barrel plug-> minifit) (Cable  + minifit connector) $3
    (requires molex crimper to assemble or soldering)
*   HDMI Monitor ( optional recommended) 7” freestanding <https://www.adafruit.com/products/1033> $159.95
*   USB Keyboard <https://secure.logitech.com/en-us/product/wireless-touch-keyboard-k400r> $30
*   USB Hub ( recommended with keyboard <http://www.newegg.com/Product/Product.aspx?Item=9SIA2BP0T23948>) $29.99

## Build instructions

1.  Drill out M6 clearance hole in bottom TurtleBot plate

1.  Assemble TurtleBot2 Kit

1.  Drill and tap an M6 hole in the bottom of the heatsink [How to Tap](http://www.wikihow.com/Use-a-Tap)

1.  Assemble DragonBoard 410c heatsink assembly  
    [Directions to create DB410c Heatsink](https://www.element14.com/community/community/designcenter/single-board-computers/blog/2016/02/01/cooling-the-dragonboard-410c-and-ifc6410p) there is more info in [this forum thread](http://www.96boards.org/forums/topic/recommended-heatsinkfan-for-410c/)

1.  Mount Astra
    The simplest mount is to drill out the center rear hole to 6mm clearance.
    And use the same 6mm bolt down to the chassis using the tripod mount.
    Point the camera forward and slightly upward.

    This will work for most simple use cases.
    Accurate mapping and navigation in larger spaces will need a more precise mounting similar to the Asus Xtion or Kinect.
    It should be elevated at the back and rigidly horizontal in the position called out by [REP 119](http://www.ros.org/reps/rep-0119.html)
    We will be developing an official recommended way to mount the Astra onto the TurtleBot.
    Please check back in the future for more details.

1.  Install Debian onto the DB410c  
    Full details at <https://www.96boards.org/db410c-getting-started/Installation/LinuxSD.md/>
    Also see <https://builds.96boards.org/releases/dragonboard410c/linaro/debian/16.04/> for more details about the release.

    1.  Download img and copy onto SD card.
    1.  Flip dip switch to boot from SD
    1.  Follow onscreen instructions
    1.  Remove media, flip the dip-switch back

1.  Install DB410c to the TurtleBot
    Screw the M6 bolt into the heatsink.

1.  Assemble the power cord.

    1.   Use a Molex crimper to attach a minifit conector to the barrel connector ponytail.  
         The barrel connector is center positive, and the positive pin is away from the clip for the molex connector. [How to assemble a molex connector](https://www.youtube.com/watch?v=L8Mfvv1PqpY)

1.  Connect power cord to the Kobuki 12v connector and DB410c board.
    Collect extra cable length between the Kobuki and the bottom plate.

1.  Install USB hub under bottom plate and connect the USB cables

    1.  The USB Hub upstream connector connects to the DB410c
    1.  Plug the Astra USB cable into the hub.
    1.  Plug connect the Kobuki USB port to the hub.
    1. Collect excess USB cable between the Kobuki and the bottom plate.
