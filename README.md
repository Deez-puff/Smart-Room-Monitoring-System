# Smart Room Temperature & Humidity Monitoring System

A reliable and cost-effective **embedded systems project** that monitors **ambient temperature and humidity in real time** using an **Arduino UNO** and **DHT11 sensor**.  
The system provides **instant visual feedback** via a **16×2 I2C LCD** and **audible alerts** using a buzzer when temperature exceeds a predefined safety threshold.

---

## Problem Statement

Monitoring indoor environmental conditions is essential for ensuring **comfort, safety, and equipment protection** in homes, laboratories, and workspaces.  
Manual monitoring is inefficient and error-prone. This project addresses the problem by providing an **automated, real-time monitoring solution** using embedded hardware.

---

## Project Objectives

- Measure room temperature and humidity accurately
- Display real-time sensor data on an LCD
- Trigger an alert when temperature exceeds a safe limit
- Provide serial output for debugging and validation
- Build a scalable foundation for future IoT upgrades

---

## System Architecture

DHT11 Sensor
↓
Arduino UNO
↓
┌─────────────────────────────┐
│ 16×2 I2C LCD → Live Display│
│ Buzzer → Alert System│
│ Serial Monitor → Debugging │
└─────────────────────────────┘



## Hardware Components

- Arduino UNO  
- DHT11 Temperature & Humidity Sensor  
- 16×2 LCD with I2C Module  
- Buzzer  
- Jumper Wires  
- USB Cable  

---

## Software & Libraries

- Arduino IDE  
- DHT Sensor Library (Adafruit)  
- Adafruit Unified Sensor Library  
- LiquidCrystal I2C Library  

---

## Working Principle

1. The DHT11 sensor continuously measures temperature and humidity.
2. Arduino UNO reads and processes the sensor data.
3. The processed values are displayed on the LCD in real time.
4. If the temperature crosses a defined threshold:
   - The buzzer is activated as an alert.
   - An alert message is shown on the LCD.
5. All readings are sent to the Serial Monitor for monitoring and debugging.

---

## Sample Output

### Normal Condition
Temp: 28°C
Hum: 60%



### Alert Condition
Temp: 32°C ALRT
Hum: 65%


 Buzzer activates when temperature exceeds the limit.

---

##  Key Features

- Real-time temperature and humidity monitoring
- Threshold-based alert mechanism
- Simple and clean hardware design
- Beginner-friendly yet extensible architecture
- Serial data logging support

---

## Applications

- Smart room and home monitoring
- Laboratory and classroom safety systems
- Environment monitoring for electronics
- Academic and embedded systems learning projects

---

## Advantages

- Low-cost implementation
- Easy to deploy and maintain
- Modular and expandable design
- Strong foundation in embedded systems concepts

---

## Limitations

- Measures only ambient temperature (not internal device temperature)
- DHT11 has limited accuracy compared to industrial sensors
- No wireless connectivity (can be enhanced with IoT modules)

---

## Future Enhancements

- IoT integration using ESP8266 / ESP32
- Mobile and web-based monitoring
- Automatic fan or AC control
- Data logging and analytics
- Cloud-based alert notifications

---

## Repository Structure

Smart-Room-Monitoring-System/
├── SmartRoomMonitor.ino
├── README.md
├── .gitignore
├── LICENSE
└── circuit.png



---

## Author

**Deepak Rajesh**  


---

## License

This project is licensed under the **MIT License**, allowing free use, modification, and distribution with attribution.


---

## Circuit 

<img width="1374" height="887" alt="Screenshot 2025-12-28 154715" src="https://github.com/user-attachments/assets/c16b9c34-81ed-499c-a27c-c1a94580977e" />

