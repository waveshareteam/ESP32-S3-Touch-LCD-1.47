# 02 SD 卡测试

[English](README.md) | [简体中文](README_ZH.md)

## 功能

Reads and writes files on a TF card and reports the result on the serial console.

## 硬件需求

- ESP32-S3-Touch-LCD-1.47 开发板

## 怎么运行

idf.py set-target esp32s3 build flash monitor

## 预期现象

The serial console reports the TF card mount and file operation results.

## 常见问题

Insert a formatted TF card before starting the example.

