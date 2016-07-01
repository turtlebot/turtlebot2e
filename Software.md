# Software Instructions

1.  Install Debian Jessie Image
    Detailed instructions are available at: <https://www.96boards.org/db410c-getting-started/Installation/LinuxSD.md/>
    This is recommended to occur before fully assembling the robot for easier access to the dip switches.
    (See above.)

1.  Install ROS Kinetic <http://wiki.ros.org/kinetic/Installation/Debian>

1.  Install turtlebot

   1.   `sudo apt-get install ros-kinetic-turtlebot-apps`

1.  In your environment set `TURTLEBOT_3D_SENSOR=astra`

1.  You can now continue to the standard [TurtleBot Tutorials](http://wiki.ros.org/Robots/TurtleBot).

## Known Differences

There are a few known differences between the TurtleBot2e and the 

*   Joystick kernel drivers need to be compiled and installed if wanted ([kernel module build instructions](https://builds.96boards.org/releases/dragonboard410c/linaro/debian/latest/))
*   Networking ARP issues([workaround](http://www.96boards.org/forums/topic/ssh-and-ping-workarounds/), [other discussion](http://www.96boards.org/forums/topic/410cubuntu-cant-ssh-in/))
