# arduino-water-tank-monitoring-system

💧 Arduino Uno Based Water Tank Monitoring & Control System using Ultrasonic Sensor

---

👨‍💻 Project Details

Name: Jewel Biju
Course: Btech in ECE
Institution: College of Engineering Kidangoor

---

📌 Project Objective

- To monitor water level using an ultrasonic sensor
- To display water level on an LCD screen
- To automatically control the water pump
- To provide alert using a buzzer when tank is full
- To reduce water wastage and manual effort

---

⚙️ Components Used

- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- 16x2 LCD Display
- Relay Module
- Water Pump (Motor)
- Buzzer
- Jumper Wires
- Power Supply

---

🧠 Working Principle

- Ultrasonic sensor measures distance of water surface

- Distance is calculated using echo time

- Arduino processes the distance value

- LCD displays available water space in tank

- If tank is full (distance < 12 cm):
  
  - Motor turns OFF
  - Buzzer turns ON

- If water level is low (distance > 30 cm):
  
  - Motor turns ON

- System runs automatically

---

🔌 Circuit Diagram

- Ultrasonic sensor connected to pins 10 (Trigger) & 11 (Echo)
- Relay module connected to pin 8
- Buzzer connected to pin 12
- LCD connected to pins 7, 6, 5, 4, 3, 2
- Motor controlled through relay

"Circuit Diagram" (diagrams/schematic.png)

---

🧩 Block Diagram

- Input: Ultrasonic Sensor
- Processing: Arduino Uno
- Output:
  - LCD Display (Water Level)
  - Relay → Motor Control
  - Buzzer (Alert)

"Block Diagram" (diagrams/block_diagram.png)

---

📊 Applications & Future Scope

Applications

- Household water tank automation
- Smart water level monitoring systems
- Industrial liquid level control
- Water conservation systems

Future Scope

- IoT integration for remote monitoring
- Mobile app notifications
- Real-time cloud data tracking
- Solar-powered system

---

🏁 Conclusion

- The system effectively monitors water level using ultrasonic sensing
- Automatically controls motor to prevent overflow and dry run
- Provides real-time display using LCD
- Buzzer alert improves safety and awareness
- Cost-effective and reliable solution for real-world use
______
