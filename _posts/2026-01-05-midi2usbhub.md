---
title: midi2usbhub
date: 2026-01-05 19:22:00 -08000
categories: [MIDI, MIDI-Hardware-Firmware]
tags: [usb-midi-host, tinyusb, serial-port-midi, midi-processing, midi-patchbay, cli, command-line, command-line-interpreter, usb-msc, rp2040, pico-w, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
image:
  path: assets/img/midi2usbhub/midi2usbhub.jpg
  alt: soldered prototype hardware inside an enclosure
---
# [midi2usbhub](https://github.com/rppicomidi/midi2usbhub)
Use a Raspberry Pi Pico to interconnect MIDI devices via a USB hub or old school MIDI.

This program uses a command line interpreter to let you route MIDI among any USB connected devices
and the serial port MIDI I/O. You can save routing configurations internally and back them up
on a flash drive. If you need to route data from a USB MIDI host like a computer running a DAW,
you should look at [midi2piousbhub](https://github.com/rppicomidi/midi2piousbhub) instead.