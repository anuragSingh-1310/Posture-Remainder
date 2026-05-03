# 📏 Screen Distance Alert System

A simple Arduino-based project that monitors the distance between a user and a screen using an ultrasonic sensor. If the user gets too close (less than 30 cm), a buzzer and LED are activated as a warning.

---

## 🚀 Features
- Real-time distance measurement using ultrasonic sensor
- Alerts user when distance < 30 cm
- Visual (LED) and sound (buzzer) feedback
- Lightweight and easy to build

---

## 🛠️ Components Used
- Arduino Uno (or compatible board)
- Ultrasonic Sensor (HC-SR04)
- Buzzer (3-pin or 2-pin)
- LED
- Resistor (for LED)
- Jumper wires

---

## 🔌 Circuit Connections

### Ultrasonic Sensor
- VCC → 5V
- GND → GND
- Trig → Pin 9
- Echo → Pin 10

### Buzzer (3-pin)
- VCC → 5V
- GND → GND
- I/O → Pin 11

### LED
- Positive → Pin 13
- Negative → GND (via resistor)

---

## 💻 How It Works
1. The ultrasonic sensor sends a sound wave.
2. It measures the time taken for the wave to return.
3. Distance is calculated using:
