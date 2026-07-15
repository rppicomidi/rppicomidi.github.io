---
title: A MIDI Controller for VCV Rack
date: 2026-07-15 14:50:00 -08000
categories: [MIDI-DIY-Project, twist4-Twist]
tags: [vcv-rack, usb-midi-device, rp2040, c-sdk, rotary-encoders, endless-encoders, graphics]     # TAG names should always be lowercase
comments: false
pin: false
---
# [twist4](https://github.com/rppicomidi/twist4) and [Twist](https://github.com/rppicomidi/Twist)

![twist4 and Twist](assets/img/twist4-and-Twist/Twist4withPlugin.jpeg)
_The twist4 hardware is shown attached to a computer running a VCV Rack patch with the Twist plugin_

The [twist4](https://github.com/rppicomidi/twist4) repository describes how to build a USB MIDI controller
with 4 endless rotary encoders, one 128x64 OLED graphics display per encoder, and two bank switch buttons.
The controller is based on a Raspberry Pi Pico board, commonly available rotary encoders with push switch,
and low-cost OLED display modules. The project provides KiCad schematics and PCB layout, and it provides
a pre-build binary image and complete source code.

The [Twist](https://github.com/rppicomidi/Twist) repository contains the binary images and source code
for a [VCV Rack](https://vcvrack.com/) plugin that integrates the twist4 system or a Novation
[SL MkIII](https://novationmusic.com/sl) keyboard's InControl mode encoders and displays with VCV Rack.
The encoders are banked, so the 4 encoders of the twist4 or the 8 encoders of the SL MkIII can be mapped
to any of up to 32 parameters among all the modules in a VCV Rack patch that contains the Twist plugin.

