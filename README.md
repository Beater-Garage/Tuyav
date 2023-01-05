# Tuyav

This library allows you to interface with the VMA354 Tuya IoT Interface.
It uses the serial port to communicate with the module.
The example explains demonstrates how to use the module.
In the folder extra you can find the protocol

# Beater-Garage Modifications

Added void Tuyav::SendUserIntValue(int ID, int value) function.
This allows an integer value to be sent and then scaled to a float in Tasmota.
Also, this branch is explicitly forked from version 1.1.0 since 1.2.0 eats up too much RAM to run on an Arduino Nano.
