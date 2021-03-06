# Awesome Hardware Reverse Engineering

A curated list of awesome reverse engineering resources to make you better! 

Managed by Reversing.ID for the reversing community.

## Introduction 

`Hardware Reverse Engineering` focus on circuitry (boards, ICs) and intercomponent relation.

The scope and level of analysis can be vary greatly, some common targets:

- firmware.
- board layout.
- chip circuit design.

Some notable process:

- teardown: product disassembly, component/subsystem identification
- interface: protocol monitoring/analysis/emulation
- firmware: extract/modify code or data
- circuit: silicon modification

## Table of Contents

- Resources
    - [Books](#books)
    - [Courses](#courses)
    - [Channels](#channels)
    - [References](#references)
    - [Protocol List](#protocol-list)
- Hadware Tools
    - [Bus Interface](#bus-interface)
    - [Logic Analyzer](#logic-analyzer)
    - [Osciloscope](#osciloscope)
    - [Dev Board](#dev-board)
    - [Radio Frequency](#radio-frequency)
    - [Magnetic Strip](#magnetic-strip)
- Software Tools
    - [EDA](#eda)
    - [Firmware Extract](#firmware-extract)
    - [Disassemblers](#disassemblers)
    - [Debuggers](#debuggers)

- - - 

## Books

Electronics, VHDL, and circuit design

* [Digital Electronics](https://amzn.com/8125939369)
* [Digital Fundamentals](https://amzn.com/0132737965)
* [Digital Design](https://amzn.com/B00HQ1CYUU)
* [The Art of Electronics](https://amzn.com/0521809266)

Hardware hacking

* [The Hardware Hacker: Advetures in Making and Breaking Hardware](https://amzn.com/159327758X)
* [Hardware Hacking: Have Fun while Voiding your Warranty](https://amzn.com/B001UN2WDY)
* [Hardware Hacking Projects for Geeks](https://amzn.com/0596003145) 
* [Game Console Hacking: Xbox, PlayStation, Nintendo, Game Boy, Atari and Sega](https://amzn.com/B001V7U7AE)

## Courses

Radio Frequency

* [Software Defined Radio with HackRF](https://greatscottgadgets.com/sdr/)

## Channels

## References

Learning Assembly

* [Low-level Code Reference](https://github.com/ReversingID/LowLevelCode-Reference) - coming soon

Development Boards

* [Arduino](https://www.arduino.cc/) | based on AVR or ARM 
* [NodeMCU](https://www.nodemcu.com) | based on ESP8266
* [Teensy](https://www.pjrc.com/teensy/) | based on ARM
* [MSP430 Launchpad](http://www.ti.com/tool/MSP-EXP430G2ET) | based on TI MSP430
* [STM32 Nucleo](https://www.st.com/en/evaluation-tools/stm32-nucleo-boards.html)

Single-Board Computer (family)

* [Raspberry Pi](https://www.raspberrypi.org/)
* [BeagleBoard](https://beagleboard.org/)
* [Onion Omega](https://onion.io/)
* [Pine64](https://www.pine64.org/)
* [ODROID](https://www.hardkernel.com)

Interface protocols

* SPI
* I2C
* JTAG
* SWD

- - - 

## Bus Interface

Multi-interface

* [Shikra](https://int3.cc/products/the-shikra) - JTAG, SPI, I2C, UART, GPIO
* [Hydrabus](https://hydrabus.com/) - UART, I2C, USB, smartcard, 2-wire, wiegand, SPI, CAN, SDIO, DAC, 1-wire
* [Bus Pirate](http://dangerousprototypes.com/docs/Features_overview) - 1-wire, I2C, SPI, JTAG, UART
* USB to TTL/UART

Programmer

* [Xpliot Nano](https://expliot.io/products/expliot-nano)
* STM32 programmer - enter DFU (Device Firmware Upgrade) mode for programming and debugging
* AVR programmer

JTAG

* [JTAGulator](https://github.com/grandideastudio/jtagulator)

CAN

* [CANtact](https://linklayer.github.io/cantact/) - CAN (Controller Area Network) to USB interface

OBD adapter

* [ObdDiag](http://www.obddiag.net/) - open source ELM327 OBD adapter, connect to On-Board Diagnostic (OBD) port for connecting to car's self-diagnostic system.
* [M2](https://www.macchina.cc/m2-introduction) - 

## Logic Analyzer

*concurrently capturing, visualizing, and decoding large quantities of digital data*

* [Logic Pirate](http://dangerousprototypes.com/docs/Logic_Pirate) - 8 channels
* [Saleae](https://www.saleae.com/)
* USB Logic Analyzer
* [BeagleBone as Logic Analyzer](https://github.com/abhishek-kakkar/BeagleLogic)

## Osciloscope

*visual display of electrical signals and how they change over time*

Standalone

* HP/Agilent
* Tektronix
* Rohde & Schwarz
* LeCroy
* Rigol

PC_based

* ProcScope
* USBee
* PicoScope

## Dev Board & Breakout Board

* [GoodFET](http://goodfet.sourceforge.net/)
* [GreatFET One](https://greatscottgadgets.com/greatfet/one/)

## Radio Frequency

*Analyze, modify, and replay Radio Frequency signal.*

General-purpose

* [HackRF](https://greatscottgadgets.com/hackrf/) - half duplex, 1 MHz - 6 GHz
* [LimeSDR](https://www.crowdsupply.com/lime-micro/limesdr) - full duplex, 
* [RTL-SDR](https://www.rtl-sdr.com/) - RX, 500 kHz - 1766 MHz
* [YARD Stick](https://greatscottgadgets.com/yardstickone/) - half duplex, 300-348 MHz, 391-464 MHz, 782-928 MHz

Zigbee

* [ApiMote](https://github.com/riverloopsec/apimote) - IEEE 802.15.4/ZigBee sniffing hardware
* [Freakduino](https://freaklabs.org/documentation/freakduino/)

Bluetooth

* [Ubertooth](https://greatscottgadgets.com/ubertoothone/)
* [Bluefruit LE Snifferluef](https://www.adafruit.com/product/2269)

RFID & NFC

* [Proxmark3](https://proxmark.com/)
* [Chameleon](https://lab401.com/products/chameleon-mini-reve-rebooted) - NFC emulation and manipulation tool
* [HydraNFC](https://hydrabus.com/hydranfc-1-0-specifications/)
* ACR-122U - RFID/NFC reader/writer

## Magnetic Strip

* [MagSpoof](https://samy.pl/magspoof/) - wireless credit card / magnetic stripe spoofer

- - -

## EDA

EDA (Electronic Design Automation) and ECAD (Electronic Computer-Aided Design)

* [Eagle](https://www.autodesk.com/products/eagle/overview)
* [KiCad](https://www.kicad-pcb.org/)
* [Altium](https://www.altium.com/)
* [Pulsonix](https://www.pulsonix.com/)

## Firmware Extract

* [Binwalk](https://github.com/ReFirmLabs/binwalk)

## Disassemblers & Decompilers

Multi-architecture

* [Radare2](http://www.radare.org/r/) // [Cutter](https://cutter.re)
* [objdump](http://linux.die.net/man/1/objdump)

## Debuggers

Hardware debugger

* [OpenOCD](http://openocd.org/) - On-Chip Debugger

Signal Analysis

* [Sigrok](https://sigrok.org/) // [PulseView](https://sigrok.org/wiki/PulseView)
* [Open Bench Logic Sniffer](http://dangerousprototypes.com/docs/Open_Bench_Logic_Sniffer)

Firmware debugger

* [GDB](https://www.gnu.org/software/gdb/)