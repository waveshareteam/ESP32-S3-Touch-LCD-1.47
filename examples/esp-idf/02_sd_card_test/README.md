# 02 SD Card Test

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Reads and writes files on a TF card and reports the result on the serial console.

## Hardware Required

- ESP32-S3-Touch-LCD-1.47 development board

## How to Run

idf.py set-target esp32s3 build flash monitor

## Expected Result

The serial console reports the TF card mount and file operation results.

## Troubleshooting

Insert a formatted TF card before starting the example.

