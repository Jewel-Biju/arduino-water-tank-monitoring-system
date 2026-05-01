# Arduino Water Tank Monitoring System

## 🚀 Overview
This project is an automated water tank monitoring and control system built using Arduino. It uses an ultrasonic sensor to measure water levels in real time and automatically controls a water pump using a relay module.

The system helps prevent:
- Water overflow
- Dry running of pump
- Manual monitoring effort

It is a low-cost, scalable solution suitable for smart home and IoT applications.

## Project Details
- **Name:** Jewel Biju
- **Course:** Btech in ECE
- **Institution:** College of Engineering Kidangoor

## Project Objective
To automate the water level monitoring system using Arduino and other related components.

## Components Used
- Arduino Uno
- Ultrasonic Sensor HC-SR04
- 16x2 LCD Display
- Relay Module
- Water Pump Motor
- Buzzer
- Jumper Wires
- Power Supply

## Working Principle
The system uses an ultrasonic sensor to measure the water level in a tank and displays the level on an LCD. It controls a water pump to fill the tank automatically when the water level is low.

The HC-SR04 ultrasonic sensor measures the distance between the sensor and water surface using sound waves.

Distance formula:
Distance = (Time × Speed of Sound) / 2

Water Level = Tank Height - Measured Distance

### Control Logic:
- If water level < 30% → Pump ON
- If water level ≥ 90% → Pump OFF
- Buzzer activates at critical levels

## 🔌 Pin Configuration

| Component        | Arduino Pin |
|-----------------|------------|
| Ultrasonic TRIG | D9         |
| Ultrasonic ECHO | D10        |
| Relay Module    | D7         |
| Buzzer          | D6         |
| LCD RS          | D12        |
| LCD EN          | D11        |

## Circuit Diagram/Schematic
![Circuit Diagram](https://github.com/Jewel-Biju/arduino-water-tank-monitoring-system/blob/main/water-tank-monitoring-schematic.jpeg)

## Block Diagram
![Block Diagram](https://github.com/Jewel-Biju/arduino-water-tank-monitoring-system/blob/main/water-tank-monitoring-block-diagram.jpeg)

## Hardware Documentation
[Hardware Documentation](https://github.com/Jewel-Biju/arduino-water-tank-monitoring-system/blob/main/water-tank-monitoring-hardware.pdf)

## 🛠️ Setup Instructions

1. Connect all components as per circuit diagram
2. Upload the Arduino code using Arduino IDE
3. Power the system using 5V supply
4. Place ultrasonic sensor at top of tank
5. Observe water level on LCD

## ▶️ How to Use
- System starts automatically
- Pump turns ON when water is low
- Pump turns OFF when tank is full

## 📊 Results

- Accurate water level detection up to ±2 cm
- Automatic pump response time < 1 second
- Successfully prevented overflow during testing

## 🔮 Future Enhancements

- Integration with IoT platforms (Blynk / Firebase)
- Mobile app for real-time alerts
- Cloud-based monitoring dashboard
- Solar-powered system for energy efficiency

## Applications
- Household water tank automation
- Smart water level monitoring systems
- Industrial liquid level control
- Water conservation systems

## 🧰 Tech Stack
- Arduino IDE
- Embedded C
- HC-SR04 Sensor
- Relay Control System

## Conclusion
This project aims to provide an efficient and automated way of monitoring and managing water levels in tanks, enhancing water conservation efforts.

## 📄 License
This project is open-source and available under the MIT License.