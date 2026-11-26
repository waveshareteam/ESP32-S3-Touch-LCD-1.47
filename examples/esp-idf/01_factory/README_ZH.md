# 出厂功能演示

[English](README.md) | [简体中文](README_ZH.md)

## 功能

运行触摸测试和 LVGL 出厂演示，包含 RGB 色彩轮播、背光调节和 Wi-Fi 扫描。

## 硬件需求

- ESP32-S3-Touch-LCD-1.47 开发板
- USB 数据线

## 怎么运行

在本示例目录中打开 ESP-IDF 终端，执行以下命令：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

触摸屏幕会留下红色笔迹。单击 BOOT 键进入演示，向左滑动可查看系统设置和 Wi-Fi 扫描页面。

## 常见问题

触摸测试会等待 BOOT 键按下。示例启动时会尝试连接 `main/main.c` 中预设的测试网络，可在 Wi-Fi 页面扫描附近的网络。
