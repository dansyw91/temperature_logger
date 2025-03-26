# Temperature and Humidity Logger

## 🚀 Overview
To read temperature and humidity data using DHT22 sensor and Arduino UNO and logs it to the serial monitor.

## 🛠️ Components
- Arduino UNO
- DHT22 sensor
- 10kΩ Pull-up Resistor
- Jumper wires

## 💾 Installations
1. Install the 'DHT' and 'Adafruit Unified Sensor' libraries.
2. Upload the code to the Arduino using Arduino IDE.
3. Open the Serial Monitor to view the data.

## 📐 Schematic
              +---------------------+
              |    Arduino Uno      |
              |                     |
              |   [5V] ----------- (VCC) -- DHT22
              |                     |
              |   [GND] ---------- (GND) -- DHT22
              |                     |
              |   [Pin 2] --------- (DATA) -- DHT22
              |                     |
              +---------------------+
                            |
                        10kΩ Resistor
                            |
                          (VCC)


## ✅ Example Output
Temperature: 25.3 °C | Humidity: 60.5 %
Temperature: 26.1 °C | Humidity: 59.7 %
Temperature: 24.8 °C | Humidity: 62.0 %
