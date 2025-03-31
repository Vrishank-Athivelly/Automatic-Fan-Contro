# Automatic-Fan-Control
Detect room temperature and turn on/off the fan using Arduino

Components Required:
Arduino Uno
DHT11 Temperature and Humidity Sensor
Relay Module (5V)
Fan (or LED for testing)
Jumper Wires
Power Supply (for the fan)

Circuit Connections:
DHT11 Sensor
VCC → 5V (Arduino)
GND → GND (Arduino)
Data → Pin 2 (Arduino)

Relay Module
VCC → 5V (Arduino)
GND → GND (Arduino)
IN → Pin 7 (Arduino)
NO (Normally Open) → One terminal of the fan
COM (Common) → Power source for the fan
