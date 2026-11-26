# Factory Demo

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Runs a touch test and an LVGL factory demo with RGB color cycling, backlight adjustment, and Wi-Fi scanning.

## Hardware Required

- ESP32-S3-Touch-LCD-1.47 development board
- USB data cable

## How to Run

Open an ESP-IDF terminal in this example directory and run:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

Touching the display draws red marks. Press BOOT once to open the demo, then swipe left to reach the system settings and Wi-Fi scan screens.

## Troubleshooting

The demo waits at the touch-test screen until BOOT is pressed. On startup, the example attempts to connect to the test network configured in `main/main.c`. Use the Wi-Fi screen to scan for nearby networks.
