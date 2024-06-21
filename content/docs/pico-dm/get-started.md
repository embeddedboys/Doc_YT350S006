+++
title = "快速上手"
weight = 2
description = """
This page tells you how to get started with the Compose theme.
"""
+++

### RaspberryPi Pico

#### 准备事项

- Pico DM YT350S006 显示拓展板
- RaspberryPi Pico 核心板
- USB Type-C 数据线

#### 固件烧录

##### 方法一

{{< picture "blink-an-led-final.gif" "blink-an-led-final.gif" "Image alt text" >}}

图解步骤：

1. 准备好要烧录的UF2文件
2. 按住核心板上的BOOTSEL按键，插入USB线缆
3. 电脑识别到名为RPI-RP2的可移动存储设备
4. 将要烧录的文件拖放至名为RPI-RP2的可移动存储设备中
5. 等待传输完成，程序自动执行

##### 方法二

需要准备一个debugprobe或CMSIS DAPLink工具。

#### 串口调试

将准备好的USB Type-C线连接至显示拓展板上的Type-C母座，另一端连接至电脑。

### Luckfox Pico Max

#### 准备事项

- Pico DM YT350S006 显示拓展板
- Luckfox Pico Max 核心板
- 100M/1000M 以太网线缆
- USB Type-C 数据线

#### 固件烧录

参考</br>
[SD 卡镜像烧录](https://wiki.luckfox.com/zh/Luckfox-Pico/Luckfox-Pico-SD-Card-burn-image)</br>
[SPI NAND Flash 镜像烧录](https://wiki.luckfox.com/zh/Luckfox-Pico/Luckfox-Pico-Flash-burn-image)

#### 串口调试