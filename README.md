

Teensy Docs
===========


My personal notes on getting the Teensy 3.6 up and running.


Hardware
--------

My Teensy 3.6 is connected to a standard Ubuntu 20.04 machine over micro-USB.

Software
--------

The first step was getting serial up and running.
Downloaded the udev rules from [here](https://www.pjrc.com/teensy/td_download.html),
and saved to `00-teensy.rules` as seen in this repository.
Following instructions, this was copied to `/etc/udev/rules.d`.
After a reboot (perhaps not necessary?), the Teensy serial port was found at `/dev/ttyACM0`.



