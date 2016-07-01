# Introduction

## Definition
The TurtleBot 2e is a new revision of the TurtleBot primarily defined by replacing the netbook with a single board computer(SBC) such as the 96 Boards CE computer, the DB410c.
It will also feature the Orbbec Astra camera. 

### Benefits

The SBC's offer two main advantages over the existing netbooks. 
The first one is that functional SBC's are now available at the $75 price point, while the necessary netbooks remain in the $400 price range.
The second advantage of the modern SBCs is that they require less power and can consequently be run off of the internal power supply from the Kobuki base.
This significantly simplifies battery management for the user.
There is only the one battery level to check, charge and discharge.

The switch to use the Orbbec Astra is an improvement since the previous two primary sensors, the Microsoft Kinect and the Asus Xtion are both out of production and becoming increasingly unavailable.

### Challenges

There are disadvantages to switching to an SBC.
Most evident externally is that the SBCs do not have an integrated keyboard or screen.

* The SBC does not have an integrated display or keyboard.

* Many fewer kernel drivers are available by default.

* The default installation is on Debian

  * This is new for the ROS community and as such untested. 

* The DB410c needs a heatsink fabricated and a mounting method. 

### Contributing

The TurtleBot is an open community project.
If you have improvements or suggestions for the TurtleBot2e please open pull requests against [this document](http://github.com/turtlebot/turtlebot2e).
If you would like to suggest anything that doesn't fit into this document directly please start a thread on the [TurtleBot Forums](http://discourse.ros.org/c/turtlebot)
