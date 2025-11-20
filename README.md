# Heartbeat-Sensor-OLED-ThingSpeak
A heartbeat monitoring project using a pulse sensor and SSD1306 OLED display. Shows real-time BPM readings and uploads the data to ThingSpeak for cloud visualization. A compact IoT health-monitoring solution combining sensors, display, and online analytics.


# ❤️ Heartbeat Sensor With OLED Display + ThingSpeak IoT Upload

This project uses a **heartbeat sensor** with an **OLED display** to show BPM in real time, while also uploading data to **ThingSpeak Cloud**.

## 📌 Features
- Reads heartbeat using Pulse Sensor.
- Displays BPM on OLED screen.
- Sends heart rate values to ThingSpeak IoT channel.
- Compact and beginner-friendly.

## 🧰 Components Used
- Arduino / ESP board (based on your code structure)
- Pulse Sensor
- SSD1306 OLED Display (I2C)
- Jumper wires

## 🔌 Wiring
### OLED Display
| OLED Pin | Board Pin |
|----------|------------|
| VCC      | 3.3V/5V    |
| GND      | GND        |
| SCL      | D1/SCL     |
| SDA      | D2/SDA     |

### Heartbeat Sensor
| Sensor Pin | Board Pin |
|------------|-------------|
| VCC        | 5V          |
| GND        | GND         |
| Signal     | A0          |

## ☁️ ThingSpeak Integration
The code sends BPM values to:
- **Channel Number:** *(set in code)*
- **Write API Key:** *(set in code)*

Update interval: ~1 second.

## ▶️ How to Use
1. Edit your ThingSpeak channel number & API key.
2. Upload the code to your board.
3. View heart rate on OLED.
4. Monitor live IoT data on ThingSpeak dashboard.

## 📄 Source Code
File: `heatbeat_sensor_with_display.ino`

---


