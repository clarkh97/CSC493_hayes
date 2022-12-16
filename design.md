
This program uses data collected from a current and voltage sensing hat attached to a Raspberry Pi. From the current and voltage values, power consumption can be calculated.
The Raspberry Pi has Raspberry Pi OS installed, which is based on Debian Linux.
- The current sensor is a hat that connects to the Pi using the GPIO pins.
- The charging cable for the target device is spliced and wired so that all of the current must run through the terminals on the current sensor.
The program which interacts with the sensor is written in Python 3.
- There is a method which measures voltage as well as another method that measures current in the library from Waveshare.
- Power is calculated by multplying current and voltage.
Once power is calculated, it is added continuously using tools from the Numpy library.
- The change in power can be detected using standard deviation which is also avalable using Numpy.
- Once the change in power is detected, a while loop will be used to continuously add the total power consumed.
- The sum of the power added inside this while loop is the amount of power that is being wasted to keep the device at a full charge.
- The number is the sum of the wattage readings divided by 3600 since the standard measurement for power consumption is watt hours, while the program measures every second.
