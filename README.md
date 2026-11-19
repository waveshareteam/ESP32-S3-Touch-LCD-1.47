# ESP32-S3-Touch-LCD-1.47

[English](README.md) | [简体中文](README_ZH.md)

1.47-inch 172 × 320 capacitive touch display board for ESP32-S3 with a JD9853 SPI display, AXS5106L I2C touch controller, 16 MB Flash, 8 MB PSRAM and a TF card slot.

| Framework | Version | Examples |
| --- | --- | ---: |
| ESP-IDF | v5.4.0 | 5 ESP-IDF projects plus the factory project |
| Arduino-ESP32 | 3.0.0 | 6 Arduino sketches |

## Quick Start

Download a ready-to-flash image from the [firmware directory](firmware/), or follow an individual example guide to build from source.

## Examples

### ESP-IDF

| Example | Main feature |
| --- | --- |
| [01_factory](examples/factory/) | Complete factory LVGL interface |
| [02_sd_card_test](examples/esp-idf/02_sd_card_test/) | SD card read and write test |
| [03_lvgl_example](examples/esp-idf/03_lvgl_example/) | LVGL interface and touch |
| [04_lvgl_image](examples/esp-idf/04_lvgl_image/) | LVGL image display |
| [05_lvgl_sd_image](examples/esp-idf/05_lvgl_sd_image/) | LVGL images loaded from a TF card |

### Arduino

| Example | Main feature |
| --- | --- |
| [01_gfx_helloworld](examples/arduino/examples/01_gfx_helloworld/) | Arduino_GFX display and text |
| [02_sd_card_test](examples/arduino/examples/02_sd_card_test/) | TF card access |
| [03_lvgl_arduino_v8](examples/arduino/examples/03_lvgl_arduino_v8/) | LVGL v8 interface |
| [04_lvgl_battery](examples/arduino/examples/04_lvgl_battery/) | Battery information UI |
| [05_lvgl_brightness](examples/arduino/examples/05_lvgl_brightness/) | Backlight brightness UI |
| [06_lvgl_image](examples/arduino/examples/06_lvgl_image/) | LVGL image display |

Libraries used by the sketches are bundled in [examples/arduino/libraries](examples/arduino/libraries/).

## Resources

- [Product page](https://www.waveshare.com/ESP32-S3-Touch-LCD-1.47.htm)
- [Product Wiki](https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-1.47)
- [Chinese documentation](https://docs.waveshare.net/ESP32-S3-Touch-LCD-1.47/)

## Support

- Example or repository problem: [open an issue](https://github.com/waveshareteam/ESP32-S3-Touch-LCD-1.47/issues/new/choose).
- Product usage, hardware or order questions: [Waveshare support](https://service.waveshare.com/).

## License

Apache License 2.0. See [LICENSE](LICENSE). Third-party components retain the licenses in their own directories.

