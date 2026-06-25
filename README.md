# LoRa Wearable IoT PCB

A compact, low-power **LoRa-enabled wearable IoT hardware platform** designed using **KiCad**. This PCB was developed by transforming our **Smart India Hackathon (SIH)** prototype into a custom embedded hardware solution.

The board integrates long-range communication, motion sensing, environmental monitoring, GPS connectivity, battery charging, and onboard power management into a compact PCB suitable for wearable and portable IoT applications.

---

## Features

* ESP32-WROOM-32E Microcontroller
* LoRa RA-02 (SX1278) Long Range Communication
* GPS Interface
* MPU6050 6-Axis IMU
* BME280 Temperature, Humidity & Pressure Sensor
* USB Type-C Power Input
* TP4056 Li-ion Battery Charging
* 3.3V Voltage Regulation
* WS2812B Programmable RGB Status LED
* SOS Push Button
* Active Buzzer
* Compact PCB Layout
* Designed in KiCad

---

## Hardware Specifications

| Component            | Description               |
| -------------------- | ------------------------- |
| MCU                  | ESP32-WROOM-32E           |
| LoRa                 | Ai-Thinker RA-02 (SX1278) |
| Motion Sensor        | MPU6050                   |
| Environmental Sensor | BME280                    |
| Battery Charger      | TP4056                    |
| Voltage Regulator    | AMS1117-3.3               |
| Communication        | LoRa + UART + I²C + SPI   |
| Power Input          | USB Type-C                |
| Power Source         | 3.7V Li-ion Battery       |

---

## Project Structure

```text
LoRa-Wearable-PCB/
│
├── Hardware/
│   ├── Schematic
│   ├── PCB Layout
│   ├── 3D PCB Model
│   └── Libraries
│
├── Images/
│   ├── PCB_3D.png
│   ├── PCB_Top.png
│   ├── PCB_Bottom.png
│   └── Schematic.png
│
├── Manufacturing/
│   ├── Gerber Files
│   ├── Drill Files
│   ├── BOM
│   └── Pick and Place
│
└── README.md
```

---

## Interfaces

### SPI

* LoRa RA-02

### I²C

* MPU6050
* BME280

### UART

* GPS Module

### GPIO

* WS2812B RGB LED
* SOS Button
* Active Buzzer

---

## Software Support

* Arduino IDE
* PlatformIO
* ESP-IDF

---

## Applications

* Smart India Hackathon Projects
* Wearable IoT Devices
* Emergency Communication Systems
* Disaster Management
* Environmental Monitoring
* Asset Tracking
* Wildlife Monitoring
* Smart Agriculture
* Remote Data Acquisition

---

## Design Software

* KiCad

---

## Current Status

* ✅ Schematic Completed
* ✅ PCB Layout Completed
* ✅ 3D PCB Model Completed
* ⏳ PCB Fabrication
* ⏳ Assembly
* ⏳ Firmware Development
* ⏳ Hardware Validation

---

## Future Improvements

* Replace AMS1117 with a low-power LDO
* Add battery protection IC
* Integrate USB-UART programmer
* Optimize RF layout
* Reduce PCB size
* Improve power efficiency

---

## License

This project is released under the MIT License.

---

## Acknowledgement

This project originated as a **Smart India Hackathon (SIH)** prototype and has evolved into a custom PCB through continuous design improvements and embedded hardware development.

---

### If you found this project interesting, consider giving the repository a ⭐.
