---
title: usb_midi_host
date: 2026-01-03 16:14:00 -08000
categories: [MIDI, MIDI-Firmware-Library]
tags: [usb-midi-host, tinyusb, rp2040, c-sdk, arduino]     # TAG names should always be lowercase
comments: false
pin: false
---
# [usb_midi_host](https://github.com/rppicomidi/usb_midi_host)
An application level [TinyUSB](https://github.com/hathach/tinyusb) USB MIDI Host driver for the RP2040.

Now that TinyUSB support USB MIDI Host internally, this driver is less useful. Once the [Adafruit_TinyUSB_Arduino](https://github.com/adafruit/Adafruit_TinyUSB_Arduino) project accepts my [pull request](https://github.com/adafruit/Adafruit_TinyUSB_Arduino/pull/561) to enable USB MIDI Host for RP2xxx family devices, I am going to archive this library.

