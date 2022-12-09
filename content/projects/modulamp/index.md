---
layout: page
date: 2021-12-24T14:16:00-08:00
title: "ModulAmp - A modular audio streaming and amplifier system"
author: Paolo
comments: false
categories:
tags: [ModulAmp]
---
(hero image here)

ModulAmp is my attempt to build an integrated audio streaming amplifier that can be upgraded over time. 

### What should it do?
* Stream from a Wi-Fi or wired connection using any number of services (Squeezelite, Spotify Connect, Bluetooth, AirPlay, DLNA, Roon, etc...)
* Integrate a two channel stereo amplifier with enough power to work in a studio or a small living room.
* Support multiple line level inputs.
* Provide a consistent and intuitive user experience.
* Be controlled remotely via MQTT.

### What is it NOT supposed to do?
* This is not a multichannel home theater amplifier. Only two channels are supported, even if there is no real reason why it could not be expanded to support multiple channels, given a proper source input and the relative number of amplifer channels.
* There is no dedicated remote. Core functionalities like volume and input selection can be done either via the control knob, or MQTT messages. Streaming functionalities can be done via a dedicated LMS controller like [Fiona](https://fionamusic.app) or [iPeng](http://penguinlovesmusic.de/ipeng-8/).

### [__Enclosure__](enclosure.md) | [__Hardware__](hardware.md) | [__Software__](software.md)


