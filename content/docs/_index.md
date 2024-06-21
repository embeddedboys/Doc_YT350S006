+++
title = "版型介绍"
weight = 1
+++

我们使用此显示面板开发了多种不同接口的显示模组

所以文档将针对不同平台分为多个部分:

#### Pico DM YT350S006 （基于Pico类接口开发板）

| Pico DM YT350S006 | Luckfox Pico Max | RaspberryPi Pico |
| --- | --- |  --- |
| 芯片 | RV1106G3 | RP2040 |
| 处理器 | Cortex A7 @1.2GHz | Cortex M0 @125MHz |
| NPU | 0.5TOPS,支持int4、in8、int16 | 无 |
| ISP | 最大输入5M @30fps | 无 |
| 内存 | 256MB DDR3L | 264KB SRAM |
| Wi-Fi+蓝牙 | 无 |
| 摄像头接口 | MIPI CSI 2-lane | 无 |
| USB | USB 2.0 Host/Device | |
| GPIO | 26 个 GPIO 引脚 |
| 默认存储介质 | SPI NAND FLASH(256MB) | 最大16MB SPI NOR FLASH |

#### RPi DM YT350S006 （基于RaspberryPi类接口开发板）

| RPi DM YT350S006 | RaspberryPi Model B |
| --- | --- |
| 芯片 | BCM2835 |
| 处理器 | ARM1176JZF-S @700MHz |
| NPU | 无 |
| GPU | Boroadcom VideoCore IV |
| ISP | 无 |
| 内存 | 256MB/512MB SDRAM （和 GPU 共享）|
| Wi-Fi+蓝牙 | 无 |
| 默认存储介质 | SD / MMC / SDIO card slot |

请根据您购买的模组及手上的开发板自行选择合适的文档。

{{< block "grid-2" >}}
{{< column >}}
{{< button "./pico-dm/" "Luckfox Pico Computer & RaspberryPi Pico Microcontroller" >}}
{{< button "./rpi-dm/" "RaspberryPi Comptuers" >}}
{{< /column >}}
{{< /block >}}

{{< picture "boards.jpg" "boards.jpg" "Image alt text" >}}

<!-- That content is better than dummy lorem ipsum 2) That content serves a good real-world demo for this theme 3) Publish more structured docs for each theme which are better than long blocky READMEs -->
