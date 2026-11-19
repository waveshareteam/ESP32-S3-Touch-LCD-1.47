# 固件

[English](README.md) | [简体中文](README_ZH.md)

这些是已在 ESP32-S3-Touch-LCD-1.47 开发板上测试过的可直接烧录合并镜像。所有文件从 `0x0` 开始烧录，文件名中的日期表示测试镜像日期。

| 文件 | 用途 |
| --- | --- |
| [ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin](ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin) | 出厂恢复固件 |
| [ESP32-S3-Touch-LCD-1.47_Factory_20250508.bin](ESP32-S3-Touch-LCD-1.47_Factory_20250508.bin) | 出厂演示镜像 |
| [ESP32-S3-Touch-LCD-1.47_SDCardTest_20250508.bin](ESP32-S3-Touch-LCD-1.47_SDCardTest_20250508.bin) | SD 卡测试示例 |
| [ESP32-S3-Touch-LCD-1.47_LVGLExample_20250508.bin](ESP32-S3-Touch-LCD-1.47_LVGLExample_20250508.bin) | LVGL 显示示例 |
| [ESP32-S3-Touch-LCD-1.47_LVGLImage_20250508.bin](ESP32-S3-Touch-LCD-1.47_LVGLImage_20250508.bin) | LVGL 图片示例 |
| [ESP32-S3-Touch-LCD-1.47_LVGLSDImage_20250508.bin](ESP32-S3-Touch-LCD-1.47_LVGLSDImage_20250508.bin) | LVGL SD 卡图片示例 |

先运行 `python -m pip install esptool` 安装 esptool，擦除 Flash，再把所选镜像从 `0x0` 写入。

```bash
python -m esptool --chip esp32s3 --port <PORT> erase_flash
python -m esptool --chip esp32s3 --port <PORT> write_flash 0x0 <IMAGE>.bin
```

已验证出厂镜像的 SHA-256 为 `E582744F9E1AEBC7550F46F4B5B221CC184D1EAD3FC8C28201B5A550AB020BE9`。
