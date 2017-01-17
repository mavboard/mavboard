mavboard
=================

Just got your MAVBoard? Check out the [Quickstart Guide](https://github.com/mavboard/mavboard/wiki/Getting-Started)!


The MAVBoard is a way to share a single MAVLink telemetry connection (the telemetry port on a 3D Robotics APM 2.X, for example) among multiple devices, such as OSDs, telemetry radios, telemetry converters or other add-on boards. Until now, the solution has been to create custom soldered cable harnesses which are difficult to make and not as flexible, since only one device can be connected to the "Tx" pin of the MAVLink connection.

The MAVBoard makes connecting several MAVLink devices a breeze. It is very easy to choose which device can access the "Tx" pin of the MAVLink connection by a simple jumper. Now your OSD, two-way telemetry radio AND FrSky telemetry can all run at the same time without the wiring being a nightmare!

The Pro model also includes on onboard Arduino compatible ATMega328P chip which has the ability to convert Mavlink data on the input into alternate RC telemetry protocols.

## Firmwares ##

This repository contains information about the MAVBoard hardware. There (will be) several firmwares that are compatible with the MAVBoard based on which RC system you use. Click below to go to the repository for the specific firmware to get instructions about how to use that firmware:

* FrSky Hub Protocol for D series Receivers (D4R-II, D8R-XP): [https://github.com/mavboard/jD-IOBoard](https://github.com/mavboard/jD-IOBoard)
* FrSky S.Port Protocol for X series Recievers (Taranis Compatible): (coming soon)
* OpenLRSng telemetry (throttled MAVLink): (coming soon)


## Typical Application ##

![Typical Application](https://raw.githubusercontent.com/mavboard/mavboard/master/images/typical_application.png)


## Pinout ##

![Pinout](https://raw.githubusercontent.com/mavboard/mavboard/master/images/mavboard_pro_pinout.png)
