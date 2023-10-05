---
title: Display Clients
description: >
  Find out about various display clients that can be used with SimpleWorship
categories: [Simple Worship]
tags: [simpleworship, display, docs]
---

# Simple Worship Display Clients

----

By default, simple worship does not actually display any of your slides on its own.

It instead hosts a "display server", and various display clients can connect to it.

This allows you to have multiple displays, and even multiple types of displays, easily.

## Display Clients

### Simple Worship Display

[solafide-dev/simpleworship-display](https://github.com/solaide-dev/simpleworship-display)

This is the most likely display client people coming from another church presentation software will use. When ran on the same machine running SimpleWorship, you can mimic the standard experience of other church presentation software.

It runs on `MacOS`, `Windows`, and `Linux`, and simply opens a window with your slides that can be full-screened.

It leverages the SSDP protocol to automatically find the display server, so you don't have to configure anything.


### Web Display

Because SimpleWorship is built on web technologies, it is possible to use any web browser as a display client.

Simply point your browser to `http://<display-server-ip>:7777` to view the slides in your browser. (Replace `<display-server-ip>` with the IP address of the machine running SimpleWorship)
