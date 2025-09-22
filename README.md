# 🍄 Smart Mushroom House Monitoring System

## Overview
IoT-based smart monitoring system for mushroom cultivation.  
Monitors environmental conditions such as temperature, humidity, CO2, and water pH.  
Data is displayed on a 20x4 LCD and uploaded in real-time to Firebase Realtime Database.

## Features
- Real-time monitoring of temperature, humidity, CO2, and pH
- Data displayed on LCD 20x4
- Automatic data upload to Firebase
- Wi-Fi connectivity for remote monitoring
- Alerts via Serial Monitor if sensor fails

## Hardware
- ESP32
- DHT22 (temperature & humidity)
- MQ135 (CO2 sensor)
- Analog pH sensor
- LCD 20x4 I2C

## Software
- Arduino IDE (C++)
- Firebase Realtime Database
- Wi-Fi network connection

## Author
Mohammad Alwi Ferdiansyah Alfarizi

## Usage
1. Configure Wi-Fi and Firebase credentials in the code.
2. Connect sensors to the defined pins on ESP32.
3. Upload code to ESP32 using Arduino IDE.
4. Open Serial Monitor to check data logs.
5. View real-time data on LCD and Firebase dashboard.
