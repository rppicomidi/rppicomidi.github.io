---
title: pico_pico_midi_lib
date: 2026-01-06 14:21:00 -08000
categories: [MIDI-Firmware-Library, pico_pico_midi_lib]
tags: [serial-port-midi, rp2040, rp2350, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [pico_pico_midi_lib](https://github.com/rppicomidi/pico_pico_midi_lib)
A C++ library for sending MIDI messages between two RP2040 devices via high speed UART.
Data move much faster than the 31.25kbs MIDI baud rate.

Projects that use this library must also link [ring_buffer_lib]({% link _posts/2026-01-03-ring_buffer_lib.md %})
