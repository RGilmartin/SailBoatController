# Bluetooth Sail Controller

Bluetooth Sail controller is a sailboat controller built by Ryan Gilmartin to control a custom made scale sailboat. This project is built on 
Bluetility, a "general-purpose Bluetooth Low-Energy utility for Mac OS X". 

Using bluetooth over traditional radio control has really no benifits (maybe more custom telemetry) but I don't have any radio control stuff
but i do have a bluetooth enabled arduino clone. Making this run on a phone would be a better idea but I'm too lazy to write all of the bluetooth connectivity code so i used some general purpose utility and modified it. In the end it's probably been more work that writing it from scatch and I'm not even done but oh well.

obviously because bluetility is open-source, this is as well

## About the boat
The boat that I am working on uses an emakefun ble nano as the main control board and two servos to control the sail and rudder. 
I will post pictures and the thingiverse link(it is 3d printed) when the build is complete.


# About Bluetility

Bluetility is a general-purpose Bluetooth Low-Energy utility for Mac OS X.  It scans for advertising peripherals, provides a interface to browse a connected peripheral's services and characteristics, and allows characteristic values to be read, written, and subscribed.
<img src="bluetility_screenshot.png" alt="Bluetility Screenshot" width="1085"/>

## Motivation
Bluetility is inspired by [LightBlue](https://itunes.apple.com/us/app/lightblue/id639944780?mt=12), a free bluetooth utility published by [Punch Through Design](https://punchthrough.com/).  Bluetility was created to resolve issues in this tool, and add missing features:

* Support copy/paste via Cmd+C and Cmd+V
* Sort peripherals by received signal strength
* View advertising data
* Automatically reconnect to disconnected peripherals when needed

Bluetility is published as open-source so that anyone can tweak or improve its functionality to meet their own needs.
