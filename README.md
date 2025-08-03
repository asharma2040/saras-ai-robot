# SARAS – Smart Autonomous Robotic AI System

SARAS (Smart Autonomous Robotic AI System) is a DIY AI-powered robot capable of basic navigation, vision, speech interaction, and autonomous behavior. This project focuses on the **hardware build**, ideal for hobbyists and AI enthusiasts looking to bring intelligence to life through robotics.

This README summarizes the hardware components, assembly steps, wiring notes, and project goals. A follow-up tutorial will cover software and AI integration.

---

## Features

- Modular 3-layer chassis (3D printed or custom material)
- Raspberry Pi (3 or 4B)
- 7-inch HDMI  display
- Voice input (USB mic)
- Audio output (USB speaker)
- Vision via Pi Camera module
- Basic motion control with DC motors
- L298N driver
- Obstacle detection using ultrasonic sensors

---

## Components List

| Component                      | Quantity | Notes |
|-------------------------------|----------|-------|
| DC Motors + Gear              | 4        | With small default tires |
| Large Tires (custom)          | 4        | For better look and grip |
| L298N Motor Driver            | 1        | For controlling DC motors |
| Raspberry Pi (any model)      | 1        | Brain of the robot |
| HDMI Display (7-inch)         | 1        | Robot face |
| USB Omni-directional Mic      | 1        | Voice command input |
| USB Speaker                   | 1        | Audio feedback |
| Jumper Wires, Standoffs       | -        | For connections and stacking |
| 18650 Batteries + Holder      | 2        | Powering motors |
| 5V Power Bank                 | 1        | Powering Raspberry Pi |
| Ultrasonic Sensors            | 3        | Obstacle detection |
| 3D Printed Body / Cardboard   | -        | Custom-designed modular chassis |

---

## Design Overview

The robot has a modular three-floor design:
- **Base layer**: Motors, wheels, L298N, battery compartment
- **Second layer**: Raspberry Pi
- **Third layer**: mic, speaker, display, and camera
- Designed in Fusion 360 

---

## Wiring Diagram

<img width="640" height="360" alt="BUILT THIS" src="https://github.com/user-attachments/assets/3aca4334-662c-4735-b3e1-43318b8df188" />

---

## Build Steps Summary

1. Attach motors to the chassis and add standoffs for tire clearance.
2. Wire motors to L298N and ensure correct polarity.
3. Add standoffs to prepare second floor.
4. Mount Raspberry Pi and connect display, mic, speaker.
5. Wire L298N to Raspberry Pi GPIO.
6. Connect power: 18650s to L298N, power bank to Pi.
7. Attach Pi Cam, ultrasonic sensors, and organize cables.
8. Power on and verify boot + movement.

---

## Author

Hi, I'm Anant, a data engineer and hobbyist — and SARAS was my first ever robotics project.  
I built it to explore what happens when you give AI a body, and I’m sharing this journey so others like me can get started too.

---

## License

MIT License – feel free to build, modify, and upgrade SARAS.
