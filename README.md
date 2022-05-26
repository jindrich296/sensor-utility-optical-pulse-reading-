
# Sensor temp and hum CWT-TH03S via RS485

Temperature and humidity sensor using CWT-TH03S sensor via RS485. I need wired sensor in sauna for temperatures above 100 celsius. This is due to technical issues with the SHT30 sensor which was often disconnecting due to lenght of wires in my sauna. 




Components:

- ESP32 or ESP8266 or similar
- Photoresistor module KY-018
- LED/diod
- battery or charger

## Wiring

| KY-018                | connected to  |
| ----------------------| ------------- |
| [S] data              | ESP32 GPIO32  |
| [middle] Power (DC5V) | ESP32 VIN     |
| [-] GND               | ESP32 GND     |


## Screenshots

![App Screenshot](https://github.com/jindrich296/sensor-utility-optical-pulse-reading-/blob/main/IMG_2035.jpg)

