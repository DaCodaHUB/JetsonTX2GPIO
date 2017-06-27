# jetsonTX2GPIO
A straightforward library to interface with the NVIDIA Jetson TX2 Development Kit GPIO  pins.

Based on Software by RidgeRun
https://developer.ridgerun.com/wiki/index.php/Gpio-int-test.c
 * Copyright (c) 2011, RidgeRun
 * All rights reserved.

and ideas from Derek Malloy Copyright (c) 2012
https://github.com/derekmolloy/beaglebone

gpio298     Pin 31      GPIO9_MOTION_INT         PULL_UP

gpio388     Pin 37      GPIO8_ALS_PROX_INT       PULL_DOWN

gpio389     Pin 33      GPIO11_AP_WAKE_BT        PULL_DOWN

gpio398	    Pin 29      GPIO19_AUD_RST           PULL_UP

gpio481     Pin 18      GPIO16_MDM_WAKE_AP       PULL_DOWN

cd jetsonTX2GPIO
./build.sh
sudo ./exampleGPIOApp
