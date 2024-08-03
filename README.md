# Going to be working on a updated version of this board with better EMI Shielding, A GPS Module, and some quality of life changes. Should have it ready in about a week or two. Feel free to suggest any changes, by opeining an issue, you would like to see.


# RP2040-Motion-Sense-Board

A microcontroller PCB based on the RP2040 MCU from Raspberry Pi with an on-board high-performance IMU, 2S LiPo battery charging circuit, 32 MB quad SPI flash memory, and a bunch of GPIO breakouts.

## Features

- ICM 42688-P IMU
- 2S LiPo battery charging circuit
- 32 MB quad SPI flash memory
- TC2030 debug port
- USB C
- ESD protection circuit
- RGB LED
- Multilple GPIO breakouts
- 1 I2C
- 4 ADC
- 1 UART

## Disclaimer

I have not personally tested this board. If you want to manufacture it, you should carefully go through the design once. Downloading this project and opening it in KiCad and running the ERC or DRC will result in many warnings, but almost all of them are safe to ignore as most of them are courtyard overlapping warnings.

