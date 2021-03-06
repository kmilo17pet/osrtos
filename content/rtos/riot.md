---
title: "RIOT"
date: 2016-11-29T11:36:58+00:00
slug: "riot"
version: "2018.04"
site-url: "http://riot-os.org/"
code-url: "https://github.com/RIOT-OS/RIOT"
last-updated: "2018-05-11"
licenses: 
- LGPLv2.1
platforms:
- MSP430
- ARM
- AVR
- MIPS
- RISC-V
components:
- LoRaWAN
- FileSystem
- Network
- 6LoWPAN
- GUI
libraries:
- SPIFFS
- FatFs
- littlefs
- Ucglib
draft: false
---
RIOT is a real-time multi-threading operating system that supports a range of devices that are typically found in the Internet of Things (IoT): 8-bit, 16-bit and 32-bit microcontrollers.

<!--more-->

### Features
- A preemptive, tickless scheduler with priorities
- Flexible memory management
- High resolution, long-term timers
- Support for AVR, MSP430, ARM7, and ARM Cortex-M on over 50 boards
- The native port allows to run RIOT as-is on Linux, BSD, and MacOS. Multiple instances of RIOT running on a single machine can also be interconnected via a simple virtual Ethernet bridge
- IPv6
- 6LoWPAN (RFC4944, RFC6282, and RFC6775)
- UDP
- RPL (storing mode, P2P mode)
- CoAP
- CCN-Lite


### Demo Projects
- [Arduino Hello World](https://github.com/RIOT-OS/RIOT/tree/master/examples/arduino_hello-world). This application demonstrates the usage of Arduino sketches in RIOT.
