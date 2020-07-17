# BlueRepli Plus Open Project

A new attack idea (and more) that can:

1. Steal contact information and call history of the target phone
2. Steal SMS verification code received by the target phone
3. Send fake text messages via the target phone

See demo video in `demo/steal-phonebook.mp4`.

## Schematic
Contains the core circuit design of BlueRepliPlus.
- schematic.pdf

## Bootloader
For booting the operating system, supporting initialization of LCD, USB and other necessary peripherals.
 - [Das U-Boot 2020.04](https://github.com/aodzip/u-boot)

## Kernel Driver
Out-of-tree Linux Kernel driver for V3 series SoC only peripherals.
 - [VideoEngine Driver](https://github.com/aodzip/cedar)

 - [MIPI-CSI2 Camera Driver](https://github.com/aodzip/sun6i-mipi-csi)
