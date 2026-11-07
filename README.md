# MotionSense: Real-Time Human Activity Tracking and Dataset System

An IoT motion-sensing node that collects walking and standing data from a gyroscope sensor, shows readings on an OLED display, and streams them to ThingSpeak over Wi-Fi.

## What it does

- Reads gyroscope data on a Raspberry Pi Pico W using MicroPython
- Logs labelled readings to CSV
- Shows live readings on an OLED display
- Uploads data over Wi-Fi to a ThingSpeak channel for real-time cloud visualisation

## Dataset

- Activities: walking and standing
- Collection: 3 sessions of 5 minutes each
- Format: CSV

## Hardware

- Raspberry Pi Pico W
- Gyroscope sensor
- OLED display

## Software

- MicroPython
- ThingSpeak (cloud monitoring)

## Setup

1. Flash MicroPython onto the Pico W.
2. Copy the project scripts to the board.
3. Add your Wi-Fi credentials and ThingSpeak API key in a local config file. Do not commit this file.
4. Run the main script to start logging and uploading.

## Repository layout

```
motionsense/
  firmware/    MicroPython scripts for the Pico W
  data/        collected CSV files
  README.md
```

## Author

Swayam Mishra
