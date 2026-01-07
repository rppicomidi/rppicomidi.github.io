---
title: cdc_stdio_lib
date: 2026-01-06 15:47:00 -08000
categories: [Utility-Firmware-Library, cdc_stdio_lib]
tags: [rp2040, rp2350, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [cdc_stdio_lib](https://github.com/rppicomidi/cdc_stdio_lib)
Library allows a pico-sdk application that uses TinyUSB to add USB CDC stdio support.

Normally, the pico-sdk will emit an error at compile time if you attempt to enable USB
stdio on the USB device port in an application that is using TinyUSB for any reason,
including using Pico PIO USB as a USB host. This library copies the essential bits
from the pico-sdk's own source code to glue the TinyUSB CDC device driver to the pico-sdk's
stdio library.