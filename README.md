# Obstacle Avoiding Car using Arduino Uno

## 1. Introduction

The **Obstacle Avoiding Car** is a robotic vehicle that detects and avoids obstacles using ultrasonic sensors. Built using an **Arduino Uno** microcontroller and geared motors, the car autonomously navigates through its environment without collisions.

This project showcases the construction, coding, and testing phases of the car.

---

## 2. Problem Statement

The objective is to design and build a self-navigating car using Arduino Uno that:

- Detects obstacles in real-time using ultrasonic or IR sensors.
- Makes smart directional decisions to avoid collisions.
- Controls motors to execute smooth turns and stops.

### Challenges:

- Real-time sensor integration.
- Motor synchronization and control logic.
- Efficient power usage and compact design.

**Applications:** indoor automation, object avoidance robots, exploration bots, and surveillance.

---

## 3. Materials Required

| Component                | Quantity | Approx. Cost (₹) |
|--------------------------|----------|------------------|
| Arduino Uno              | 1        | 570              |
| Ultrasonic Sensor (HC-SR04) | 1     | 200              |
| L293D Motor Driver IC    | 1        | 350              |
| DC Geared Motors         | 4        | 100              |
| Wheels                   | 4        | 50               |
| Breadboard               | 1        | 100              |
| Battery Pack (Li-ion)    | 1        | 230              |
| Jumper Wires & Misc      | -        | 80               |


---

## 4. Construction Process

1. Assemble the chassis and fix all components (Arduino, battery, motor driver, etc.).
2. Connect DC motors to the L293D motor driver.
3. Mount the ultrasonic sensor at the front and connect it to Arduino.
4. Use a breadboard to wire power and signal connections.
5. Connect power sources: one for motors and one for Arduino.
