# 固件

[English](README.md) | [简体中文](README_ZH.md)

这是在 ESP32-S3-Touch-LCD-1.47 开发板上完成实测、可直接烧录的出厂固件合并镜像，烧录地址为 `0x0`。

| 文件 | 用途 |
| --- | --- |
| [ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin](ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin) | ESP32-S3-Touch-LCD-1.47 出厂恢复固件 |

先运行 `python -m pip install esptool` 安装 esptool，擦除 Flash，再从 `0x0` 写入镜像。

```bash
python -m esptool --chip esp32s3 --port <PORT> erase_flash
python -m esptool --chip esp32s3 --port <PORT> write_flash 0x0 ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin
```

SHA-256：`E582744F9E1AEBC7550F46F4B5B221CC184D1EAD3FC8C28201B5A550AB020BE9`
