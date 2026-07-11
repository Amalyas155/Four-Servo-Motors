## Four Servo Motors 

A simple Arduino project that controls four servo motors. The project demonstrates how multiple servo motors can be connected and controlled using an Arduino Uno. The circuit was designed and tested using Tinkercad before implementation.

---

## Project Overview

This project uses an Arduino Uno to control four servo motors. Each servo receives a control signal from a different digital pin while sharing the same power and ground connections.

---

## Components

* Arduino Uno
* 4 × Servo Motors
* Breadboard
* Jumper Wires
* USB Cable

---

## Software

* Arduino IDE
* Tinkercad

---

## Tinkercad Simulation

You can view the circuit simulation here:

**https://www.tinkercad.com/things/4y014Cr1Jm5-four-servo-motors-control?sharecode=PhxB0buvo4stfJ60Br4KdGYm011dcT9TkjMsLlLQAvM**

---

## Circuit Connections

| Servo   | Signal Pin |
| ------- | ---------- |
| Servo 1 | D9         |
| Servo 2 | D10        |
| Servo 3 | D11        |
| Servo 4 | D12        |

* All servo VCC pins → 5V
* All servo GND pins → GND

---

## How to Run

1. Open the Arduino code in Arduino IDE.
2. Connect the Arduino Uno to your computer.
3. Select the correct board and COM port.
4. Upload the code.
5. The four servo motors will move according to the program.

---

## Repository Structure

```text
├── code/
│   └── servo_control.ino
├── images/
│   ├── circuit.png
│   └── wiring.jpg
└── README.md
```

---

## Output

<img width="1064" height="568" alt="Servo Motors Simulation" src="https://github.com/user-attachments/assets/49d33a25-4385-4220-8afb-533a02235a79" />

## Author
**Amal yasser**
**Computer and Network Engineering Student
University of Jeddah**
