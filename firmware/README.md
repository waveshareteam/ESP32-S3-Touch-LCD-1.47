# Firmware

[English](README.md) | [简体中文](README_ZH.md)

Ready-to-flash factory firmware tested on the ESP32-S3-Touch-LCD-1.47 board. The merged image is flashed at `0x0`.

| File | Purpose |
| --- | --- |
| [ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin](ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin) | Factory recovery firmware for the ESP32-S3-Touch-LCD-1.47 board |

Install esptool with `python -m pip install esptool`, erase the flash, then write the image at `0x0`.

```bash
python -m esptool --chip esp32s3 --port <PORT> erase_flash
python -m esptool --chip esp32s3 --port <PORT> write_flash 0x0 ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin
```

SHA-256: `E582744F9E1AEBC7550F46F4B5B221CC184D1EAD3FC8C28201B5A550AB020BE9`
