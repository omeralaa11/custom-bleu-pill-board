# Custom Blue Pill Board

This project is a custom-designed version of the popular Blue Pill development board based on the STM32F103C8T6 microcontroller. The design aims to provide a compact, reliable, and easily manufacturable board for embedded systems projects and educational use.

## 🚀 Objective

Redesign the STM32 Blue Pill board to:

- Improve component layout and manufacturability
- Remove unnecessary components for simplicity
- Ensure full compatibility with STM32 development tools and bootloaders

## 📦 Features

- **Microcontroller**: STM32F103C8T6 (ARM Cortex-M3, 72 MHz, 64KB Flash, 20KB RAM)
- **Power Input Options**: USB or external 5V
- **Reset & Boot Buttons**: Onboard tactile switches
- **Debugging**: SWD header for programming and debugging
- **LEDs**: Power and user LEDs for basic feedback
- **Crystal**: 8 MHz external crystal oscillator
- **Compact Form Factor**: Optimized layout for smaller size

## 🛠️ Tools Used

- **EDA Software**: KiCad 9
- **Microcontroller**: STM32F103C8T6
- **Programming**: STM32CubeIDE / STM32CubeProgrammer / PlatformIO

## ✅ Status

- ✅ Schematic Complete
- ✅ PCB Layout Finalized
- ✅ Gerbers Generated
- ⬜️ PCB Assembled and Tested *(Update this once tested)*

## 📌 Future Improvements

- Add reverse-current protection
- Consider support for higher-pin STM32 variants
- Add footprint for optional external Flash/EEPROM

