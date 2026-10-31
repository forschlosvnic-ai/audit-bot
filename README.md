[index.html](https://github.com/user-attachments/files/34212679/index.html)
# Road & Railway Audit Bot

A smart car-based robot that detects potholes on roads and cracks on railway
tracks to prevent accidents.

**Live website:** https://forschlosvnic-ai.github.io/audit-bot/

## How it works
- **Rail mode (self-guided):** two IR sensors keep the car on the track and
  notice a sudden break in the reflection, which means a crack.
- **Road mode (phone-controlled):** the car is driven from a phone while an
  ultrasonic sensor measures the distance to the road. A sudden jump means a
  pothole.
- An ESP32 reads the sensors, takes decisions and controls the motor driver.

## Components
ESP32, 2 IR sensors, 1 ultrasonic sensor, motor driver, car body with DC
motors and battery.

## What's in this repo
`index.html`: the project website (interactive demo, data charts, news links
and blog). No build step needed; just open the file in a browser.

## Team
Aditya Dwivedi and Sparsh Gupta, Class 11B
Onkareshwar Saraswati Vidya Niketan, Kanpur
Mentor: Mr. Pyarelal Sir

> A small science model shows the idea; real safety needs certified equipment.
