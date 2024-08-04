# IOT-Flow-Monitoring-System

### Introduction
This project introduces an IoT-based Water Monitoring System using NodeMCU, YFS201 flow sensor, and a 4-pin OLED display. It allows real-time monitoring of water flow rate and volume, both on-site and remotely via ThingSpeak.

### Components Required
- NodeMCU ESP8266
- YF-S201 Hall-Effect Water Flow Sensor
- 0.96" I2C OLED Display
- Connecting Jumper Wires

### Connections

#### YF-S201 Flow Sensor

| Pin         | NodeMCU Pin  |
|-------------|---------------|
| Data        | GPIO2 (D4)    |
| Power (5V)  | Vin           |
| Ground      | GND           |

#### OLED Display

| Pin         | NodeMCU Pin  |
|-------------|---------------|
| SDA         | GPIO4 (D2)    |
| SCL         | GPIO5 (D1)    |
| Power (3.3V)| 3.3V          |
| Ground      | GND           |

### Uses
- **Home Automation:** Monitor water consumption to promote conservation.
- **Industrial Applications:** Measure liquid discharge and automate processes.
- **Agriculture:** Optimize irrigation with real-time water flow data.
- **Environmental Research:** Monitor natural water bodies for conservation.

### Resources
- [IoT Water Flow Meter using ESP8266 & Water Flow Sensor](https://how2electronics.com/iot-water-flow-meter-using-esp8266-water-flow-sensor/)
- Arduino IDE
- ChatGPT
