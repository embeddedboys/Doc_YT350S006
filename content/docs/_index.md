+++
title = "版型介绍"
weight = 1
+++

我们使用此显示面板开发了多种不同接口、平台的显示拓展板

所以文档将针对不同平台分为多个部分:

### Pico DM YT350S006，基于Raspberry Pi Pico类接口开发板

支持的开发板及其配置：
| Pico DM YT350S006 | Luckfox Pico Max      | Raspberry Pi Pico       | Milk-V Duo |
|-------------------|-----------------------|------------------------| --- |
| 芯片              | RV1106G3              | RP2040                 | - |
| 处理器            | Cortex A7 @1.2GHz     | Cortex M0 @125MHz      | - |
| NPU               | 0.5 TOPS              | 无                     | - |
| ISP               | 最大输入5M @30fps     | 无                     | - |
| 内存              | 256MB DDR3L           | 264KB SRAM             | - |
| Wi-Fi+蓝牙        | 无                    | PicoW版本有            | - |
| 摄像头接口        | MIPI CSI 2-lane       | 无                     | - |
| USB               | USB 2.0               | USB 2.0 FS/LS          | - |
| GPIO              | 26                    | 30                     | - |
| 存储介质          | SPI NAND FLASH(256MB) | 最大16MB SPI NOR FLASH | - |

### RPi DM YT350S006，基于Raspberry Pi类26Pin接口开发板

支持的开发板及其配置（仅列出已验证过的）：
| RPi DM YT350S006 | RaspberryPi B                   | RaspberryPi 5              |
|------------------|---------------------------------|----------------------------|
| 芯片             | BCM2835                         | BCM2712                    |
| 处理器           | ARM1176JZF-S @700MHz            | 4 x Arm Cortex A76 @2.4GHz |
| NPU              | 无                              | 无                         |
| GPU              | Boroadcom VideoCore IV          | 未知                       |
| 内存             | 256MB/512MB SDRAM （和 GPU 共享） | 1/2/4/8 GB                 |
| Wi-Fi+蓝牙       | 无                              | 有                         |
| 存储介质         | SD / MMC / SDIO card slot       | nvme PCIE disk             |

请根据您购买的模组及手上的开发板自行选择合适的文档。

{{< block "grid-2" >}}
{{< column >}}
{{< button "./pico-dm/" "Luckfox Pico Computer & Raspberry Pi Pico Microcontroller" >}}
{{< button "./rpi-dm/" "Raspberry Pi Comptuers" >}}
{{< /column >}}
{{< /block >}}

{{< picture "IMG_20240621_064648.jpg" "IMG_20240621_064648.jpg" "Image alt text" >}}

<!-- That content is better than dummy lorem ipsum 2) That content serves a good real-world demo for this theme 3) Publish more structured docs for each theme which are better than long blocky READMEs -->
