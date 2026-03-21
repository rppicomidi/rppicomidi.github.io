---
title: midi2usbhost
date: 2026-03-21 11:44:00 -08000
categories: [MIDI-DIY-Project, midi2usbhost]
tags: [usb-midi-host, freertos, tinyusb, serial-port-midi, rp2040, rp2350, c-sdk, arduino]     # TAG names should always be lowercase
comments: false
pin: false
---
# [midi2usbhost](https://github.com/rppicomidi/midi2usbhost)
I updated this project to include C source code that uses FreeRTOS and the RP2040's UART hardware FIFOs
to see if it improves responsiveness. It is in the [FreeRTOS](https://github.com/rppicomidi/midi2usbhost/tree/main/FreeRTOS)
project subdirectory. The FreeRTOS version relies on LED indicators only.
