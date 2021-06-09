# 6502 Computer based on Ben Eater

While following along Ben Eater's 6502 video series, I attempted to follow along with a breadboard version. However, I found that connecting wires across the breadboard was often confusing and I had to debug a mis-connection more than once. To make things easier on myself, I set out to design my own PCB, following the schematics he had posted on his [website](https://eater.net/6502).

![](images/breadboard-version.jpg)

## 6502 Main PCB

The main PCB follows Ben Eater's 6502 series, comprising the 6502 processor, 62256 SRAM, 28C256 EEPROM, and 65C22 Interface Adapter. Additionally, I incorporated his 555 based clock generator, and PS2 interface.

## VGA PCB

This follows Ben Eater's [World's Worst Video Card](https://eater.net/vga) series

## EEPROM Programmer

This is simply a PCB version of the [EEPROM Programmer](https://github.com/beneater/eeprom-programmer).