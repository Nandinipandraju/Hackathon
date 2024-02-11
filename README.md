# Arduino Temperature and Humidity Monitor with Fan Control

This Arduino project allows you to monitor temperature and humidity levels using a DHT11 sensor and control a fan based on temperature readings. The readings are displayed on a 16x2 LCD screen.

## Components Used
- Arduino board (e.g., Arduino Uno)
- DHT11 temperature and humidity sensor
- 16x2 LCD screen with I2C backpack
- DC fan
- Jumper wires

## Dependencies
- [DHT Sensor Library](https://github.com/adafruit/DHT-sensor-library)
- [LiquidCrystal_I2C Library](https://github.com/johnrickman/LiquidCrystal_I2C)

## Circuit Diagram
![Circuit Diagram](circuit_diagram.png)

## Installation and Setup
1. Connect the components as shown in the circuit diagram.
2. Install the required libraries:
   - DHT Sensor Library
   - LiquidCrystal_I2C Library
3. Upload the provided Arduino sketch to your Arduino board.
4. Adjust pin configurations if necessary in the sketch.

## Usage
- Upon uploading the sketch to the Arduino board, the system will start monitoring temperature and humidity levels.
- The LCD screen will display the current temperature and humidity readings.
- If the temperature exceeds 35°C, the fan connected to pin 3 will turn on automatically to cool down the environment.
- Monitor the readings on the LCD screen and observe fan behavior accordingly.
