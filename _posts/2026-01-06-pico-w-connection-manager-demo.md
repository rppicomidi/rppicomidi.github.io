---
title: pico-w-connection-manager-demo
date: 2026-01-06 14:26:00 -08000
categories: [Demo, Demo-Firmware-Application]
tags: [tinyusb, cli, command-line, command-line-interpreter, pico-w, web-server, lwip, rp2040, c-sdk]     # TAG names should always be lowercase
comments: false
pin: false
image:
  path: assets/img/pico-w-connection-manager-demo/Pico-w-connection-manager-home.png
  alt: pico-w-connection-manager-demo embedded webserver home page
---
# [pico-w-connection-manager-demo](https://github.com/rppicomidi/pico-w-connection-manager-demo)
Run an LwIP webserver on a Pico W using a C++ Pico_w_connection_manager class and command line
interface to manage connection to the AP.

The CLI program allows you to scan for SSID, handle connect and disconnect, read RSSI, and store
SSID info in Pico W program flash using the LittleFs file system.
