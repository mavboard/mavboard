mavboard
=================

The MAVBoard is a way to share a single MAVLink telemetry connection (the telemetry port on a 3D Robotics APM 2.X, for example) among multiple devices, such as OSDs, telemetry radios, telemetry converters or other add-on boards. Until now, the solution has been to create custom soldered cable harnesses which are difficult to make and not as flexible, since only one device can be connected to the "Tx" pin of the MAVLink connection.

The MAVBoard makes connecting several MAVLink devices a breeze. It is very easy to choose which device can access the "Tx" pin of the MAVLink connection by a simple jumper. Now your OSD, two-way telemetry radio AND FrSky telemetry can all run at the same time without the wiring being a nightmare!

The Pro model also includes on onboard Arduino compatible ATMega328P chip which is also connected to the MAVLink hub that performs protocol translation on the MAVLink stream and output the translated signal to a dedicated set of pins. There is existing code (based on JDrone's jD_IOBoard_FrSkyMAVLink code) today that can translate MAVLink into the FrSky hub protocol so you can the FrSky FLD-02 and see useful telemetry values right on your RC transmitter!


