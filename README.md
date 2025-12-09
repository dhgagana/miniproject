🚗⚡ Vehicle Power Generation Using Piezoelectric Sensor (Arduino)
📌 Project Overview

This project demonstrates a piezoelectric energy harvesting system that converts mechanical pressure from vehicle movement into electrical energy. Piezoelectric sensors generate voltage when pressure is applied, which is measured using an Arduino Uno and displayed on a 16×2 LCD. The project highlights the potential of renewable energy generation from road traffic.

🎯 Objectives

To generate electrical energy using piezoelectric sensors

To convert mechanical energy into electrical energy

To measure generated voltage using Arduino

To display voltage and power on an LCD

⚙️ Working Principle

When mechanical pressure is applied to a piezoelectric sensor, it produces an electrical voltage due to the piezoelectric effect. The generated AC voltage is converted into DC using a rectifier circuit and stored in a capacitor. The Arduino reads the voltage through its analog pin, calculates the corresponding power output, and displays the values on an LCD.

🧩 Block Diagram
Vehicle Pressure
      ↓
Piezoelectric Sensor
      ↓
Rectifier Circuit
      ↓
Filter Capacitor
      ↓
Arduino Uno
      ↓
LCD Display

🔧 Hardware Components

Arduino Uno

Piezoelectric Disc Sensor

Diodes (Rectifier)

Capacitor

16×2 LCD Display

Resistors

Breadboard

Jumper Wires

💻 Software Requirements

Arduino IDE

Arduino Programming Language (Embedded C)

📈 Results

The system successfully generates electrical energy when pressure is applied to the piezoelectric sensor. The output voltage varies with the applied force and is displayed in real time on the LCD.

✅ Applications

Smart roads and highways

Speed breakers

Toll booths

Street lighting systems

Energy harvesting applications

🚀 Future Improvements

Using multiple piezo sensors to increase output power

Adding battery or supercapacitor for energy storage

Implementing wireless monitoring

Scaling for real-world road applications

📂 Repository Contents

Arduino source code

Circuit/block diagrams

Project documentation

🙌 Conclusion

This project proves that piezoelectric energy harvesting is a feasible method to generate renewable energy from vehicle movement. With proper scaling, it can contribute to smart and sustainable infrastructure.
