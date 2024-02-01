# Arduino Nano 33 BLE Sense

This repository is a collection of hacks and updated capabilities for SoC Arduino Nano 33 BLE Sense

## LSM9DS1

The standard library does not support the maximum acceleration sample rate. This modified version, which changes the values in the control registers following the parameters of the product data sheet, achieves the highest performance, but it also raises power consumption.
