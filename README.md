# *Power Tester*
## Description/Motivation
**[Project Concept](concept.md)**

## Scope
I intend for the scope of my project to reach toward a product that is usable by by someone other than myself, with no requirement for technical knowledge other than plugging in a charging cable and starting a program. Making a stand-alone device is certainly out of the scope of the semester, so it will remain on a breadboard. Eventually I would like to make a small self contained device, perhaps even have it powered by the current from the charging cable for the device being measured. By the end of the semester, I expect to have a device that can measure the power being consumed by a device through a USB power cable as well as detect when a device is trickle charging just to maintin a full battery.

## Vision
My vision for this project is a standalone device with a built-in display which would show the user power consumption as well as other parameters. The readout would display the voltage and current in real time, as well as running total of the power, and power consumed while trickle charging if applicable at the time. It would require the user to plug their desired device to track into my product, the plug the other end of the cable into a USB power supply.

My project is intended to measure the power of a device consumed while charging, and differentiating between trickle charging to maintain level and charging at normal speed. The goal of keeping track of such metrics is to calculate how much power is consumed while a device is plugged into a charger, but already at full capacity.

### Prerequisites

This program will run on a Raspberry Pi using a current sensor hat. Anyone intending to use the software will need a Raspberry Pi along with a current sensor hat as well as a chargin cable that has been cut in two in order to get the voltage and current readings through the cable.

**[Requirements](requirements.md)**

## Built With
- Python 3
- Numpy library
- Raspberry Pi OS

## Author

- **Hayes Clark**: *Power Tester* [Github](https://github.com/clarkh97/)

**[Design](design.md)**

## Acknowledgments

- Power sensor code library from Waveshare: https://www.waveshare.com/wiki/Current/Power_Monitor_HAT

[Installation and use guide](install.md)


