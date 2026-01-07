---
title: usb_midi_device_multistream
date: 2026-01-06 14:51:00 -08000
categories: [MIDI-Firmware-Library, usb_midi_device_multistream]
tags: [usb-midi-device, tinyusb, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [usb_midi_device_multistream](https://github.com/rppicomidi/usb_midi_device_multistream)
Extensions for the TinyUSB USB MIDI device driver enable multiple virtual cables.

The native TinyUSB USB MIDI class device driver for TinyUSB one supports one virtual cable
in and one virtual cable out. This library provides a header file to help you create a
USB MIDI descriptor with up to 16 virtual MIDI IN cables and 16 virtual MIDI OUT cables.
It optionally supports string descriptor labels for all of the MIDI virtual cables. Finally,
it provides the function tud_midi_demux_stream_read() that facilitates de-multiplexing each
virtual cable's MIDI messages received from USB Host's USB MIDI OUT endpoint.
