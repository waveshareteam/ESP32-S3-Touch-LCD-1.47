# Factory Firmware

[中文](./README_ZH.md)

| File | Purpose |
| --- | --- |
| [ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin](ESP32-S3-Touch-LCD-1.47_FactoryOnly_20250508.bin) | Factory recovery firmware dated 2025-05-08. Flash from `0x0`. |

Before flashing:

- Back up device-specific data that must be preserved.
- Confirm the board model and hardware revision.
- Follow the offset and flashing procedure in the product documentation for this image. Do not infer the factory image from a source build.
- Do not mix this image with a bootloader or partition file built for another project.

This image was verified on the corresponding product with Flash Download Tool. SHA-256: `E582744F9E1AEBC7550F46F4B5B221CC184D1EAD3FC8C28201B5A550AB020BE9`.

See the [firmware guide](https://github.com/waveshareteam/esp32-repo-template/blob/main/docs/spec.md) for the difference between factory firmware and source-build firmware.

## Update the Factory Image

Replacing a factory binary is a development operation. Record its source, expected hardware revision, flashing procedure, checksum, and user-visible version in the Pull Request. Never overwrite an existing image with an unrelated local build.
