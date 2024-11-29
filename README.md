# 🎛️ Raspberry Pi OSC Communication & GPIO Sensor Control

This repository documents my work on building a multi-device system using **Raspberry Pi**, OSC communication, and **Neopixel LED Cube** control. Additionally, it includes my experience in working with GPIO sensors on Raspberry Pi.

## 🛠️ Projects Overview

### 1. LED Cube Control with OSC Communication
- **System Setup**:  
  - Built a system with **5 Raspberry Pi devices** using a **server-client architecture**.  
  - The **server** controls the LED animations and sends commands via **OSC (Open Sound Control)** protocol.  
  - Each **client** Raspberry Pi processes the OSC messages to control a section of a **Neopixel LED Cube**.  

- **Features**:  
  - Smooth animation control across all connected devices.  
  - Synchronized lighting effects for the LED cube using OSC signals.  
  - Real-time responsiveness for dynamic LED animations.  

- **Technologies**:  
  - **Python** for OSC communication and Neopixel LED control.  
  - **Raspbian OS** for Raspberry Pi devices.  
  - **Adafruit Neopixel Library** for LED programming.

### 2. GPIO Sensor Integration
- Gained hands-on experience in working with **Raspberry Pi GPIO pins**.  
- Successfully connected and controlled various sensors, including:  
  - **Motion sensors**  
  - **Proximity sensors**  
  - **Temperature and humidity sensors**  

- Wrote Python scripts to:  
  - Read sensor data using GPIO pins.  
  - Trigger actions based on sensor inputs (e.g., LED patterns, notifications).  
  - Ensure stable communication with hardware components.

## 📋 How to Use

### LED Cube Control
1. **Setup the Server**:  
   - Run the `server.py` script on the main Raspberry Pi.
   - Configure OSC message routes for each client device.

2. **Setup the Clients**:  
   - Deploy the `client.py` script on each Raspberry Pi controlling part of the LED Cube.  
   - Ensure proper network configuration for OSC communication.

3. **Run the System**:  
   - Start the server and clients.  
   - Control LED animations from the server to create synchronized effects.

### GPIO Sensor Control

## 🧰 Tools & Libraries
- **Python**  
- **Adafruit Neopixel Library**  
- **python-osc** for OSC communication  
- **RPi.GPIO** for GPIO sensor control 

