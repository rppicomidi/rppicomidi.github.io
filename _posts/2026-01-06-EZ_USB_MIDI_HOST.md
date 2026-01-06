---
title: EZ_USB_MIDI_HOST
date: 2026-01-06 09:54:00 -08000
categories: [MIDI, MIDI-Firmware-Library]
tags: [usb-midi-host, tinyusb, rp2040, rp2350, c-sdk, arduino]     # TAG names should always be lowercase
comments: false
pin: false
---
# [EZ_USB_MIDI_HOST](https://github.com/rppicomidi/EZ_USB_MIDI_HOST)
Add the Arduino MIDI Library API to the usb_midi_host TinyUSB MIDI Host driver.

This library has a pending pull request to integrate it with the native Adafruit_TinyUSB_Arduino USB MIDI host
code instead. I will integrate it and drop dependency on the usb_midi_host library when Adafruit_TinyUSB_Arduino
enables its own USB MIDI Host code for the rp2xxx family of processors.