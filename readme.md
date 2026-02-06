# KB16-01

#### This repo will only supports Rev2.

- **Revision 2**: Using APM32F103CBT6 (clone STM32F103CBT6).

When you try to go bootloader mode, QMK Toolbox will showing this message `STM32Duino device connected: LeafLabs Maple 003 (1EAF:0003:0201)`. So please compile Revision 2 and flash after that.

#### To compile

- **install qmk toolkit**: 
- qmk setup
- sudo apt install git build-essential gcc-arm-none-eabi binutils-avr avr-libc gcc-avr

- **git clone this repo**: git clone https://github.com/jcsagar/kb16
- **cd to directory**: cd kb16
- **Run**: qmk compile -kb doio/kb16/rev2 -km default