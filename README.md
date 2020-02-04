# YAAABWAN

Yet Another Accelerometer Adapter (But With Arduino Nano)

This project is a modified version of https://github.com/mhackney/YAAA (Yet Another Accelerometer Adapter) for using an HE280 hotend with a card that do not accept a Z endstop sensor plugged via I²C.

The original project here was modified by @Ybalrid to use the regular Wire.h library from Arduino, and tested on @Hayaweh's 3D printer.

We are using an Arduino Nano for this modification. If you use another Arduino the same code **should work** but you need to check the pins that are normally used for the I²C (TWI) interface.
