---
title: pico-mono-ui-lib
date: 2026-01-03 13:12:00 -08000
categories: [Graphics-Firmware-Library, pico-mono-ui-lib]
tags: [mono-ui-lib, rp2040, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
image:
  path: assets/img/pico-mono-ui-lib/pico-mono-ui-lib.jpg
  alt: Scrollable text menu on a 128x64 SSD1306-based mono OLED
---
# [pico-mono-ui-lib](https://github.com/rppicomidi/pico-mono-ui-lib)
A simple C++ UI library intended to run on a 128x64 dot OLED or similar. It provides
UI elements like menus, numeric entry, and nested views. It relies on a graphics
library to do the actually drawing on the screen.

It has been tested with [pico-ssd1306-mono-graphics-lib](https://github.com/rppicomidi/pico-ssd1306-mono-graphics-lib).