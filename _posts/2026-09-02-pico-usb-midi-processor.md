---
title: pico-usb-midi-processor
date: 2026-09-02 12:04:00 -08000
categories: [MIDI-DIY-Project, pico-usb-midi-processor]
tags: [usb-midi-host, tinyusb, usb-midi-device, midi-processing, cli, command-line, command-line-interpreter, usb-msc, rp2040, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [pico-usb-midi-processor](https://github.com/rppicomidi/pico-usb-midi-processor)
I have updated [pico-usb-midi-processor](https://github.com/rppicomidi/pico-usb-midi-processor)
Features:
- Pre-built binary releases for Raspberry Pi Pico board.
- Works with Pico-SDK version 2.3 and TinyUSB 0.18.0.
- Added two new MIDI processor functions that should allow it to implement the hack
described in [How To Hack Rekordbox DJ To Use Any Controller’s Jogwheels](https://djtechtools.com/2017/05/08/hack-rekordbox-use-controllers-jogwheels/)
    - Raw Message Remap
    - Chan Mes Range Offset
- Updated README.md to describe the new prcessor functions and how to build code in the Pico-SDK 2.3 environment.


