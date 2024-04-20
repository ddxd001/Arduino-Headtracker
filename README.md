# Arduino-Headtracker
------
目前发布demo版本，经测试可以使用

arduino板子需使用 Arduino Nano v3 328P

MPU-6050模块

PJ316 3.5mm音频视频母座

由于nano板性能不足，暂时无法支持使用0.96寸oled显示屏


使用方法，下载PCB压缩包文件，在嘉立创中打板（相关操作参考Bilibili教程）
        将arduino板、mpu6050、音频座焊接
        将code文件夹中的 .ino 文件通过arduinno ide传到开发板即可
        （需要准备的库：MPU6050、PPMEncoder及相关库）
