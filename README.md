Learning-IoT-HTTP
=================

Source code for the HTTP chapter of the book "Learning Internet of Things".

This chapter covers the basics of the HTTP protocol. It also shows how to use HTTP in the sensor, actuator and controller projects, each running on separate Raspberry Pis.

The source code contains the following projects:

* Actuator   - The actuator project. Controlls a sequence of digital outputs as well as an alarm output.
* Controller - The controller project. Controls the actuator based on input received from the sensor.
* Sensor     - The sensor project. Measures and logs temperature, light and movement.
* SensorN    - Shows the evolution of the sensor project. 1<=N<=6.
* Clayster.Library.IoT - Library handling basic interoperability for the Internet of Things.
* Clayster.Library.RaspberryPi - Library containing classes handling different types of devices connected to the Raspberry Pi interfaced through GPIO.

Projects are developed in C# and compiled using Xamarin. They are executed on Raspberry Pi using MONO. By modifying the classes in Clayster.Library.RaspberryPi, the code can be made to run on other hardware platforms as well. This library is the only library that contains code specifically written for the Raspberry Pi.
