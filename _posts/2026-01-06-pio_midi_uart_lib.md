---
title: pio_midi_uart_lib
date: 2026-01-06 19:53:00 -08000
categories: [MIDI-Firmware-Library, pio_midi_uart_lib]
tags: [serial-port-midi, rp2040, rp2350, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [pio_midi_uart_lib](https://github.com/rppicomidi/pio_midi_uart_lib)
This library adds up 4 PIO-based MIDI serial ports to a Rasberry Pi Pico and 6 PIO-based
MIDI serial ports to a Raspberry Pi Pico 2. Each serial port has both MIDI IN and MIDI OUT.
Data I/O is interrupt driven and is designed to be read and written from a simple loop.

If you need more MIDI OUT than MIDI IN, you can create a PIO MIDI OUT port without creating
a MIDI IN port for up to 8 MIDI OUT and no MIDI IN on a Pico and 12 on a Pico 2.

Projects that use this library must also link [ring_buffer_lib]({% link _posts/2026-01-03-ring_buffer_lib.md %})
