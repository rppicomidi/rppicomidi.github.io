---
title: usb_midi_dev_ac_optional
date: 2026-01-03 19:13:00 -08000
categories: [MIDI, MIDI-Firmware-Library]
tags: [usb-midi-device, tinyusb, rp2040, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [usb_midi_dev_ac_optional](https://github.com/rppicomidi/usb_midi_dev_ac_optional)
A TinyUSB application USB MIDI Device driver that permits no AUDIO CONTROL in the descriptor.

This is a specialized driver for TinyUSB that enables mimicking a USB MIDI device that does
not have an Audio Control Interface descriptor in its configuration descriptors.
