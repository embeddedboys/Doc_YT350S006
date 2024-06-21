+++
title = "SDK环境部署"
weight = 3
description = """
This page tells you how to get started with the Compose theme.
"""
+++

### RaspberryPi Pico

#### 部署 Pico-SDK

1. 安装前置依赖
```shell
sudo apt install cmake ninja-build gcc-arm-none-eabi libnewlib-arm-none-eabi libstdc++-arm-none-eabi-newlib
```

2. 下载 Pico-SDK 源码
```shell
git clone https://gitee.com/embeddedboys/pico-sdk $HOME/pico-sdk
```

3. 拉取 Pico-SDK 子仓库代码
```shell
cd ~/pico-sdk

git submodule update --init
```

4. 配置环境变量
```shell
echo "export PICO_SDK_PATH=$HOME/pico-sdk" >> ~/.bashrc

source ~/.bashrc
```
对于zsh
```shell
echo "export PICO_SDK_PATH=$HOME/pico-sdk" >> ~/.zshrc

source ~/.zshrc
```

#### 获取工程
```shell
git clone https://gitee.com/embeddedboys/pico_dm_yt350s006_freertos
```

Micropyton （开发中）

#### 编译及配置
```shell
cd pico_dm_yt350s006_freertos

mkdir -p build
cd build
cmake .. -G Ninja
ninja
```

### Luckfox Pico

参考[SDK 环境部署（PC端）](https://wiki.luckfox.com/zh/Luckfox-Pico/Luckfox-Pico-SDK)搭建环境