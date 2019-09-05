# KiCAD Template for designing a keyboard based on the ST32F3 series MCU

A mechanical keyboard template for use with KiCAD v5 to jumpstart design based on the [STM32F303](https://www.st.com/en/microcontrollers-microprocessors/stm32f303.html), an ARM Cortex M4 based processor. The basic schematic implements an ESD (electro-static discharge) protection circuit, crystal, USB-C type connector, support for underglow, overcurrent and overvoltage input protection, and a hardware switch to trigger bootloader mode.

Separate files are provided for the key matrix as well as the underglow LED matrix. All that is left for the enduser is to implement the matrix for both switches and LED underglow and map them appropriately to the MCU using hierarchical labels.

Keyboard Maintainer: [Ian Canino](https://github.com/CaninoDev)  
Components Included: LED Underglow, ESD Protection, LED MX/Alps switches, crystal