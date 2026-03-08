---
title: TinyUSB_MIDI_Device_Arduino
date: 2026-03-08 07:35:00 -08000
categories: [MIDI-Firmware-Library, TinyUSB_MIDI_Device_Arduino]
tags: [usb-midi-device, arduino, midi]     # TAG names should always be lowercase
comments: false
pin: false
---
# Introducing [TinyUSB_MIDI_Device_Arduino](https://github.com/rppicomidi/TinyUSB_MIDI_Device_Arduino)
This library implements a TinyUSB MIDI device driver for the Arduino
[MIDI Library](https://github.com/FortySevenEffects/arduino_midi_library)
that supports multiple virtual cables. The source includes an example that shows how to make
a USB MIDI device with 2 virtual MIDI cables. See the project's [README](https://github.com/rppicomidi/TinyUSB_MIDI_Device_Arduino/README.md) for more details.

This library uses more code space and memory than the Adafruit TinyUSB Library's API. If you are creating
a USB MIDI device with only one virtual MIDI cable, consider using the Adafruit TinyUSB Library's native
MIDI device API instead.

I created this library in response to a
[Discussion post](https://github.com/adafruit/Adafruit_TinyUSB_Arduino/discussions/502) in the
[Adafruit TinyUSB Library](https://github.com/adafruit/Adafruit_TinyUSB_Arduino) project.
The question asked how to communicate over multiple virtual cables using a USB MIDI device
created with the library's API. As Adafruit TinyUSB Library version 3.7.4 was implemented,
the answer is that you cannot. Although you can create a proper multi-virtual MIDI cable USB descriptor,
the library's API does not give you access to virtual cables other than cable 0. This library
is an attempt to solve the problem.
