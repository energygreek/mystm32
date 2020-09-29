# 使用vscode 编译和调试stm32f4 单片机程序

## 前提

1. 下载交叉编译工具，可以到[arm官网](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads) 下载最新版本，放到同级目录

2.  使用`STM32CubeMX` 生成本项目

3. 安装 `c/c++`, `Cortex-Debug` 两个插件

## 使用方法

1. 在命令行执行make 命令， 需要指定`GCC_PATH` 到交叉编译bin目录，或者直接写到makefile
2. 点击vscode的调试按钮
