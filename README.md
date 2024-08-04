# IOT-Flow-Monitoring-System


### Introduction
This project introduces an IoT-based Water Monitoring System using NodeMCU, YFS201 flow sensor, and a 4-pin OLED display. It allows real-time monitoring of water flow rate and volume, both on-site and remotely via ThingSpeak.

### Components Required
- NodeMCU ESP8266
- YF-S201 Hall-Effect Water Flow Sensor
- 0.96" I2C OLED Display
- Connecting Jumper Wires

### Connections

| Component              | NodeMCU Pin      |
|------------------------|------------------|
| YF-S201 Flow Sensor    | GPIO2 (D4)       |
| OLED Display SDA       | GPIO4 (D2)       |
| OLED Display SCL       | GPIO5 (D1)       |
| YF-S201 Power          | Vin (5V)         |
| OLED Display Power     | 3.3V             |

### Uses
- **Home Automation:** Monitor water consumption to promote conservation.
- **Industrial Applications:** Measure liquid discharge and automate processes.
- **Agriculture:** Optimize irrigation with real-time water flow data.
- **Environmental Research:** Monitor natural water bodies for conservation.

### Resources
- [IoT Water Flow Meter using ESP8266 & Water Flow Sensor](https://how2electronics.com/iot-water-flow-meter-using-esp8266-water-flow-sensor/)
- Arduino IDE
- ChatGPT
