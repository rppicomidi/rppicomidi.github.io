---
title: pico-usb-midi-processor
date: 2026-11-23 16:20:00 -08000
categories: [MIDI-DIY-Project, pico-usb-midi-processor]
tags: [usb-midi-host, tinyusb, usb-midi-device, midi-processing, cli, command-line, command-line-interpreter, usb-msc, rp2040, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
---
# [pico-usb-midi-processor](https://github.com/rppicomidi/pico-usb-midi-processor)
I have updated [pico-usb-midi-processor](https://github.com/rppicomidi/pico-usb-midi-processor) to
test an updated version of the processing architecture. See [PUMP Processing Architecture Rev 2](https://github.com/rppicomidi/pico-usb-midi-processor/blob/main/doc/PUMP-Processing-Architecture-Rev-2.md). The new architecture enables multi-packet processor inputs and outputs, free-running processing tasks, and routing packets between USB MIDI virtual cables.

I had to update every MIDI processor file, so I may have introduced bugs. Once I do more testing, I will update the documentation some more and generate a release. The release may contain more processing functions.

## Processors added
- Pitch Bend to CC mapper: Maps a pitch bend message to one or two CC messages.
- Clock Generator: generate MIDI clock messages between 24 and 240 beats per minute
The [README](https://github.com/rppicomidi/pico-usb-midi-processor#list-of-midi-processors) does not yet document the new processors.

## Documents created
- [PUMP Processing Architecture Rev 2](https://github.com/rppicomidi/pico-usb-midi-processor/blob/main/doc/PUMP-Processing-Architecture-Rev-2.md)
- [Writing your own MIDI Processor](https://github.com/rppicomidi/pico-usb-midi-processor/blob/main/doc/Writing-your-own-MIDI-Processor.md)

Thanks to [TylorShine](https://github.com/TylorShine) for [requesting](https://github.com/rppicomidi/pico-usb-midi-processor/issues/4) some of the features that drove the architecture
update 
