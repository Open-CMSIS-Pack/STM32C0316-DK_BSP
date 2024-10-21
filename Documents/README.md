# STM32C0316-DK Discovery board

## Overview

The STM32C0316-DK Discovery kit is a complete demonstration and development platform for STMicroelectronics Arm® Cortex®-M0+ core-based STM32C031C6 microcontroller, with 32 kbyte of flash memory and 12 Kbytes of SRAM.

The STM32C0316-DK Discovery kit goal is to provide alternative features to the corresponding NUCLEO-C031C6 board.

All 20 pins common to all STM32C0 Series microcontrollers are user-accessible. The user can override the SWD debug pins by disconnecting the debug probe. The 5-way analog rock switch and LED can be overridden with a slide switch to be taken over by the user. All the pins are accessible through the DIP28 connector. Headers are not provided to let the user choose the header type. The 32768 Hz on-board 1-pin clock generator for RTC can be cut with a slide switch. The kit helps migrate from 8-bit to STM32C0 Series microcontrollers, and between STM32C0 Series and STM32G0 Series microcontrollers. The DIP28 pinout is designed to be as compatible as possible with the ATMEGA328 8-bit microcontroller. The LQFP48 footprint is compatible with STM32G031/071/0B1 Series microcontrollers. The UFQFPN20 footprint is compatible with STM32C01 Series microcontrollers. The WLCSP20 footprint is compatible with STM32G051 Series microcontrollers. The STM32C031C6 Series microcontroller can be tested over its operating range. The 5.0 to 3.3 V regulator bypass itself when its source goes lower than 3.3 V. The debug probe level shifters adjust the debug signal levels to the target microcontroller supply voltage.

Standalone STLINK-V3MINIE debugger/programmer tiny probe for STM32 microcontrollers.

## Getting started

- [User manual](https://www.st.com/resource/en/user_manual/um2969-discovery-kit-with-stm32c031c6-mcu-stmicroelectronics.pdf)

### ST-LINK driver installation and firmware upgrade (on Microsoft Windows)

1. Download the latest [ST-LINK driver](https://www.st.com/en/development-tools/stsw-link009.html).
2. Extract the archive and run `dpinst_amd64.exe`. Follow the displayed instructions.
3. Download the latest [ST-LINK firmware upgrade](https://www.st.com/en/development-tools/stsw-link007.html).
4. Extract the archive and run the `ST-LinkUpgrade.exe` program.
5. Connect the board to your PC using a USB cable and wait until the USB enumeration is completed.
6. In the **ST-Link Upgrade** program, press the **Device Connect** button.
7. When the ST-LINK driver is correctly installed, the current ST-LINK version is displayed.
8. Press the **Yes >>>>** button to start the firmware upgrade process.

## Technical reference

- [STM32C031C6 microcontroller](https://www.st.com/en/microcontrollers-microprocessors/stm32c031c6.html)
- [STM32C0316-DK board](https://www.st.com/en/evaluation-tools/stm32c0316-dk.html)
- [User manual](https://www.st.com/resource/en/user_manual/um2969-discovery-kit-with-stm32c031c6-mcu-stmicroelectronics.pdf)
- [Data brief](https://www.st.com/resource/en/data_brief/stm32c0316-dk.pdf)
- [Schematic](https://www.st.com/resource/en/schematic_pack/mb1716-c031c6-a03_schematic.pdf)
