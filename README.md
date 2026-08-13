# Servo Motor Tester PCB

A custom 555-timer-based Servo Motor Tester PCB designed to generate an adjustable PWM signal for testing servo motors. The PCB was designed using KiCad, including schematic capture, PCB layout, routing, and Gerber generation.

## 📌 Project Overview

This project implements a simple and compact servo motor testing circuit using the NE555P timer IC.

The circuit generates a PWM control signal whose duty cycle can be adjusted using a potentiometer. This allows the connected servo motor to be tested at different positions.

The project was designed as a complete PCB workflow, starting from schematic design and continuing through component placement, routing, PCB visualization, and Gerber generation.

## ⚙️ Key Features

- 555-timer-based PWM generation
- Adjustable PWM signal using a potentiometer
- Servo motor testing and position control
- LED power/status indication
- Dedicated power input connector
- 3-pin servo motor output connector
- Custom PCB layout
- Routed PCB traces
- Gerber files generated for PCB manufacturing

## 🧩 Components Used

- NE555P Timer IC
- RV1 Potentiometer
- R1, R2, R3 Resistors
- D1 LED
- D2 Diode
- C1 22 µF Capacitor
- 2-pin Power Input Connector
- 3-pin Servo Motor Connector
- PWR_FLAG
- GND

> Component values are based on the KiCad schematic included in this repository.

## 🔌 Circuit / Schematic

The schematic was designed in KiCad using an NE555P timer circuit to generate an adjustable PWM signal for servo motor control.

The potentiometer is used to adjust the PWM signal supplied to the servo motor.

<img width="1155" height="813" alt="image" src="https://github.com/user-attachments/assets/fce58032-04a6-4071-b46f-aefd16a4705a" />

## 🖥️ PCB Layout

The PCB layout was designed in KiCad with organized component placement and routed copper traces.

<img width="1165" height="800" alt="Screenshot 2026-08-13 175817" src="https://github.com/user-attachments/assets/043345d6-dbd3-41d0-9e74-00f622b71534" />

## 🧱 3D PCB View

The completed PCB was visualized using KiCad's 3D Viewer to verify component placement and board design.

<img width="1314" height="879" alt="image" src="https://github.com/user-attachments/assets/081cfe3d-e5cc-4c66-bbf7-712bf00ae745" />

## 📦 Gerber Files

Gerber files were generated from the final KiCad PCB design for PCB manufacturing.

The Gerber files include the required fabrication and drill data for manufacturing the board.

## 🛠️ Design Workflow

1. Schematic design
2. Component selection and footprint assignment
3. PCB component placement
4. PCB routing
5. Design Rule Check (DRC)
6. 3D PCB visualization
7. Gerber generation

## 🔧 Tools Used

- KiCad
- Schematic Editor
- PCB Editor
- 3D Viewer
- Gerber Viewer
