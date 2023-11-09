# Firmware

This is the firmware folder for the WatchClean project. Here you can place all your files for the firmware of the maschine.
Basically the firmware is splittet into 2 parts.

## Part 1: Motorcontroller

The motor controller is a module based on a ATMega328 controlling the stepper motors for the rotary plate and the lifting motor. Besides it's also controlling the cleaning basket motor. There are some input for fork light sensors and micro switches, pointing to the null position of the different Steppers. 

## Part 2:  UI Processor

The UI Processor (ESP32 based) controlling the LC Display and the input keys. It's also containing the different program steps for the cleaning processes, and has an USB Interface for external control and firmware update. 

## 