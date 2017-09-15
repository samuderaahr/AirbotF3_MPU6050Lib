# AirbotF3_MPU6050Lib
Yet another MPU6050 Library modified specifically for STM32F303CC mounted on Airbot F3 board. Probably works on other STM32F3xxRx/Cx family MCUs too with some modifications.

Airbot F3 (v1.0 Lite) is an Acro-class flight controller based on SPRacing F3. It uses 72MHz Cortex M4 (with FPU!), an MPU6050 (+HMC5883L+BMPxxx on non-acro version), and on-board 16MB (128Mbit) SPI flash. Combined with dimension of 5x5 it is just perfect for any space-constrained microcontroller project requiring more processing power and/or memory than an arduino minis but can't afford the luxury of Pixhawk-esque form factor.

Would be used and tested against Keil-MDK5. Hopefully won't break on you cool ARM-GCC guys~

Based on (seemingly abandoned): STM32_MPU6050lib by Harinadha: https://github.com/Harinadha/STM32_MPU6050lib, and Cleanflight's MPU6050 implementation.
