[![Build Status](https://travis-ci.org/kylegordon/DrivewayLights.png?branch=master)](https://travis-ci.org/kylegordon/DrivewayLights)

Driveway Lights Project
=======================

This uses JeeNode ID2, and a Dimmer plug. The dimmer plug is connected to a series of 2N7000 MOSFETS, and directly controls 3 12V LED lights on the house wall.

Port 1 - Unused (but potentially used for digital input 4 as the rear light switch or something else)
Port 2 - Defective due to burnt out digital pin 5
Port 3 - Dimmer plug - overhangs defective Port 2
Port 4 - Used for digital input 7 for the front light switch

2N7000 MOSFETS - one per channel. Common positive on the bottom screw terminal

WIRING
======

Front Cable
-----------
Blue + Blue/White = Front LED
Green + Green/White = Front Switch

Rear Cable
----------
Blue + Blue/White = Middle LED
Green + Green/White = Rear LED
