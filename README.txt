ECG_Tab
===========
ECG_Tab is an Android app which was derived from a modification of 'Blue Serial' (see below).  It was designed to be used with an Arduino UNO carrying two shields: 1) Adafruit EZ-Link Bluetooth and 2) Olimex EKG/EMG. The app will display an electrocardiogram on a Samsung Galaxy S2 Tablet; it is a NetBeans project.

About 'Blue Serial' (Initial code which has been modified)
=================
Blue Serial is an Android app which is compatible and tested on Android versions 2.2 to 4.2.2. The app itself is designed to allow for Serial communications over Bluetooth to devices such as Arduino. It has been tested with the JY-MCU serial bluetooth module but there is no reason to believe that it won't work with any other device.

It is fairly straightforward and allows for 2 way communication.  Source code at https://github.com/plastygrove/BlueSerial.git

Arduino sketch
===============
Also contained in this folder is the Arduino sketch: ECG_Tab.  Copy/paste this source code into an Arduino IDE.
