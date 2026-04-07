# 🛰️ Digital Twin Radar System

> 🏆 1st Place — IEEE IES Industrial System Recovery Hackathon

## 📌 Overview
A Digital Twin Radar System that simulates real-time industrial 
environment mapping using Arduino and an ultrasonic sensor. 
Sensor data is streamed and visualized as a live sweeping radar 
interface, creating a digital twin of the physical surroundings.

## 🛠️ Components
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- MATLAB (visualization)

## ⚙️ How It Works
1. Servo motor sweeps the ultrasonic sensor 180°
2. Arduino reads distance at each angle
3. Data is sent via Serial to MATLAB
4. Processing renders a live radar display

## 📂 Files
- `radar.ino` — Arduino sketch
- `radar_display.m` — Processing visualization

## 👤 Author
**Olatunde David Durojaiye**  
[GitHub](https://github.com/rubiks001) | [LinkedIn](linkedin.com/in/olatunde-david-durojaiye-bb5985207)
