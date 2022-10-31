![main](https://i.imgur.com/UNmNM9j.jpg)

# Dual-channel RS232-USB
This device was designed as a quick to use support tool in my workshop. 


## Features

The converter allows two simultaneous RS232 connections with variable voltage levels (can be switched between 3.3V and 5V). Individual serial buses can be turned off with a switch to easily distinguish each COM port. As this is a prototyping tool, serial connections are made with small wire hooks. The device works off a single USB-C port and includes status LEDs.

## Electrical Design
![pcb](https://i.imgur.com/V900IiL.jpg)

Design is based around two FTDI FT232RL chips, that are internally connected to a basic USB2.0 HUB IC. Each FTDI chip can be artificially unplugged from the hub via a switch. Power is fed straitght through the USB-C port.

![img4](https://i.imgur.com/8TGZren.jpg)

## Pictures

![img2](https://i.imgur.com/CDhkREt.jpg)
![img3](https://i.imgur.com/IRdUHNN.jpg)
