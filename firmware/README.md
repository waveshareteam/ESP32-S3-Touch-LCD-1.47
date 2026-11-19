# Firmware

[English](README.md) | [简体中文](README_ZH.md)

Ready-to-flash merged images tested on the ESP32-S3-Touch-LCD-1.47 board. Each file is flashed at `0x0`; the date in the file name identifies the tested image.

| File | Purpose |
| --- | --- |
| [ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin](ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin) | Factory recovery firmware |
| [ESP32-S3-Touch-LCD-1.47_Factory_20250508.bin](ESP32-S3-Touch-LCD-1.47_Factory_20250508.bin) | Factory demo image |
| [ESP32-S3-Touch-LCD-1.47_SDCardTest_20250508.bin](ESP32-S3-Touch-LCD-1.47_SDCardTest_20250508.bin) | SD card test example |
| [ESP32-S3-Touch-LCD-1.47_LVGLExample_20250508.bin](ESP32-S3-Touch-LCD-1.47_LVGLExample_20250508.bin) | LVGL display example |
| [ESP32-S3-Touch-LCD-1.47_LVGLImage_20250508.bin](ESP32-S3-Touch-LCD-1.47_LVGLImage_20250508.bin) | LVGL image example |
| [ESP32-S3-Touch-LCD-1.47_LVGLSDImage_20250508.bin](ESP32-S3-Touch-LCD-1.47_LVGLSDImage_20250508.bin) | LVGL SD card image example |

Install esptool with `python -m pip install esptool`, erase the flash, then write the selected image at `0x0`.

```bash
python -m esptool --chip esp32s3 --port <PORT> erase_flash
python -m esptool --chip esp32s3 --port <PORT> write_flash 0x0 <IMAGE>.bin
```

The verified factory image has SHA-256 `E582744F9E1AEBC7550F46F4B5B221CC184D1EAD3FC8C28201B5A550AB020BE9`.
