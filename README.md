This is a fork of https://github.com/fra589/grbl-Mega-5X.

It has a modification with the homing orders. The original firmware home the 4 axis one by one, which may stretch the hotwire to extreme length and make some troubles. According to the modifications, the horizontal axis are homed at the same time, then are the vertical axis. You can also change the order due to your machine by modifying "config.h".

You can use PlatformIO to build and upload the firmware.
