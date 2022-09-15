DS18b20 Temperature Sensor with Arduino

The DS18B20 temperature sensor is a one-wire digital temperature sensor. This means that it just requires one data line (and GND) to communicate with the Arduino.

It can be powered by an external power supply or it can derive power from the data line (called “parasite mode”), which eliminates the need for an external power supply.

DS18B20 Temperature Sensor Pinout Pins Diagram
The following table shows how you should wire the DS18B20 sensor to your Arduino board:

DS18B20	Arduino
GND	GND
DQ	Any digital pin (with 4.7k Ohm pull-up resistor)
VDD	5V (normal mode) or GND (parasite mode)

Each DS18B20 temperature sensor has a unique 64-bit serial code. This allows you to wire multiple sensors to the same data wire. So, you can get temperature from multiple sensors using just one Arduino digital pin.

