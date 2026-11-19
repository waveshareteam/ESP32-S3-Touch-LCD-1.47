# ESP32-S3-Touch-LCD-1.47

[English](README.md) | [简体中文](README_ZH.md)

ESP32-S3 1.47 英寸 172 × 320 电容触摸显示开发板，搭载 JD9853 SPI 显示控制器、AXS5106L I2C 触摸控制器、16 MB Flash、8 MB PSRAM 和 TF 卡槽。

| 开发框架 | 版本 | 示例数 |
| --- | --- | ---: |
| ESP-IDF | v5.4.0 | 5 个 ESP-IDF 工程和 1 个出厂工程 |
| Arduino-ESP32 | 3.0.0 | 6 个 Arduino 草图 |

## 快速开始

从 [固件目录](firmware/) 下载可直接烧录的镜像，或按单个示例的说明从源码构建。

## 示例

### ESP-IDF

| 示例 | 主要功能 |
| --- | --- |
| [01_factory](examples/factory/) | 完整的出厂 LVGL 界面 |
| [02_sd_card_test](examples/esp-idf/02_sd_card_test/) | SD 卡读写测试 |
| [03_lvgl_example](examples/esp-idf/03_lvgl_example/) | LVGL 界面和触摸 |
| [04_lvgl_image](examples/esp-idf/04_lvgl_image/) | LVGL 图片显示 |
| [05_lvgl_sd_image](examples/esp-idf/05_lvgl_sd_image/) | 从 TF 卡加载 LVGL 图片 |

### Arduino

| 示例 | 主要功能 |
| --- | --- |
| [01_gfx_helloworld](examples/arduino/examples/01_gfx_helloworld/) | Arduino_GFX 显示和文字 |
| [02_sd_card_test](examples/arduino/examples/02_sd_card_test/) | TF 卡访问 |
| [03_lvgl_arduino_v8](examples/arduino/examples/03_lvgl_arduino_v8/) | LVGL v8 界面 |
| [04_lvgl_battery](examples/arduino/examples/04_lvgl_battery/) | 电池信息界面 |
| [05_lvgl_brightness](examples/arduino/examples/05_lvgl_brightness/) | 背光亮度界面 |
| [06_lvgl_image](examples/arduino/examples/06_lvgl_image/) | LVGL 图片显示 |

草图使用的库随仓库提供，位于 [examples/arduino/libraries](examples/arduino/libraries/)。

## 资料

- [产品页](https://www.waveshare.com/ESP32-S3-Touch-LCD-1.47.htm)
- [产品 Wiki](https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-1.47)
- [中文文档](https://docs.waveshare.net/ESP32-S3-Touch-LCD-1.47/)

## 支持

- 示例或仓库问题：[提交 issue](https://gitee.com/waveshare/ESP32-S3-Touch-LCD-1.47/issues)。
- 产品使用、硬件或订单问题：[微雪技术支持](https://service.waveshare.com/)。

## 许可证

Apache License 2.0，详见 [LICENSE](LICENSE)。第三方组件保留其目录中的原许可证。

