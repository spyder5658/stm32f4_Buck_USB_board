# STM32F4-Based 4 layered Board with Dual Power Supply and Protection Features
## Overview
This project showcases a custom STM32F4-based board designed with robust power management and advanced PCB architecture. The board features dual power supply options, reverse polarity protection, a buck converter, and a power indicator LED. Additionally, it boasts a 4-layer PCB design, enhancing signal integrity and ensuring efficient power distribution, making it ideal for high-performance embedded systems.

## Key Features
- Microcontroller: STM32F4 series (ARM Cortex-M4)
- 4-Layer PCB Design:
  - Improved signal integrity and EMI performance.
  - Enhanced power distribution for more stable operation.
- Dual Power Supply Options:
- USB-powered for convenient operation.
- Battery-powered for portable applications.
- Reverse Polarity Protection: Protects the circuit from damage due to incorrect battery polarity.
- Buck Converter: Efficient DC-DC conversion to supply the STM32F4 and other peripherals.
- Power-On LED: Visual indicator to confirm that the board is powered.

## Snapshots
![STM32F4 Based Board](https://github.com/spyder5658/stm32f4_Buck_USB_board/blob/main/Stm32F4_based_board.png)
## Applications
- Prototyping and development of embedded systems.
- IoT (Internet of Things) applications requiring reliable power management.
- Low-power, battery-operated devices.
- Educational and research projects on embedded systems.
## Power Supply Details
- USB Power: Provides power through the standard USB connector.
- Battery Power: Connect a battery for portable applications. The board includes a reverse polarity protection circuit to safeguard against incorrect battery connections.
- Buck Converter: The on-board buck converter ensures efficient power delivery, stepping down the battery voltage to the required level for the STM32F4.


## Powering the Board:
Plug in via USB for direct power.
Alternatively, connect a battery (ensure proper polarity).
The Power-On LED will light up if powered correctly.
## Programming the STM32F4:
Use ST-Link or DFU for firmware uploading.
Refer to the STM32CubeIDE Documentation for setting up your development environment.
## Flashing the Firmware:
To flash the firmware onto the STM32F4, use the following:
```
st-flash write firmware.bin 0x08000000
Replace firmware.bin with your compiled binary file.
```
