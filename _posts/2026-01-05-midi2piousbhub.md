---
title: midi2piousbhub
date: 2026-01-05 19:33:00 -08000
categories: [MIDI, MIDI-Hardware-Firmware]
tags: [usb-midi-host, tinyusb, usb-midi-device, serial-port-midi, bluetooth-midi, bluetooth-le-midi, midi-patchbay, cli, command-line, command-line-interpreter, usb-msc, rp2040, pico-w, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [midi2piousbhub](https://github.com/rppicomidi/midi2piousbhub)
Use a Raspberry Pi Pico to interconnect MIDI devices via a USB hub or old school MIDI, or Bluetooth-LE,
or a DAW as a USB device.

This program uses a command line interpreter to let you route MIDI among any USB connected devices,
a Bluetooth-LE MIDI device, and the serial port MIDI I/O. You can save routing configurations
internally and back them up on a flash drive. If you do not need Bluetooth but do need the USB
device port, then you can use a regular Pico board instead of a Pico-W.

The CLI lets you route devices like this.
```
USB ID      Port  Direction Nickname    Product Name
0499-1622    1      FROM    lead-out    reface CS
0499-1622    1       TO     lead        reface CS
1C75-02CA    1      FROM    keys        Arturia Keylab Essential 88
1C75-02CA    1       TO     keys-in     Arturia Keylab Essential 88
1C75-02CA    2      FROM    faders      Arturia Keylab Essential 88
1C75-02CA    2       TO     faders-in   Arturia Keylab Essential 88
0000-0000    1      FROM    Drumpads    MIDI IN A
0000-0000    1       TO     TR-707      MIDI OUT A
0000-0001    1      FROM    DAW-OUT     PC MIDI
0000-0001    1       TO     DAW-IN      PC MIDI
0000-0002    1      FROM    iPad-OUT    BT MIDI
0000-0002    1       TO     iPad-IN     BT MIDI
```
See the project README.md for more information.