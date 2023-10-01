# EmoeSynth
A diy low-cost high performance RF signal source covering from DC to 6GHz.

添加了BSP驱动 V1.0，使用的板子是stm32g431-nucleo32官方开发板，开发环境使用的是Keil5。

## 初始测试
按照文件中的提示接好线，进入工程进行编译下载，打开串口，可以看到寄存器的读取结果，随后进入40MHz-70MHz的扫频循环。
