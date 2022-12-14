---
layout: page
date: 2021-01-24T14:16:00-08:00
title: "Jeeves - A gentle home automation system"
author: Paolo
comments: true
categories: [Jeeves]
tags: []
---
A home automation system

## MQTT broker

(Raspberry Pi + mosquitto)

## ambient display

(Raspberry Pi + laptop display + MagicMirror<sup>2</sup>)

## sensors

* [room sensor](roomsensor.html)
* [moisture sensor](moisturesensor.html)
* [message box](messagebox.html)

## tested boards

There's no reason why any microcontroller board would not work with Jeeves. So far, these are the ones that I tested and worked properly:

* [Wemos D1 Mini](https://www.wemos.cc/en/latest/d1/d1_mini.html#) ([purchase](https://www.amazon.com/KeeYees-ESP8266-ESP-12F-Development-Compatible/dp/B08ZY7Q7TW), [latest driver](https://www.wemos.cc/en/latest/ch340_driver.html), [local driver copy](assets/CH341SER_WIN_3.5.ZIP), [schematics](assets/sch_d1_mini_v4.0.0.pdf), [pin layout](assets/d1_mini_v4.0.0_5_16x9.png))
* [NodeMCU](https://www.nodemcu.com/index_en.html) ([purchase](https://www.amazon.com/AITRIP-NodeMcu-Internet-Development-Micropython/dp/B08B4P9LB7), [latest driver](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers), [local driver copy](assets/CP210x_Universal_Windows_Driver.zip), [spec sheet](assets/ESP8266-NodeMCU-Datasheet.pdf), [pin layout](assets/NodeMCU_schematics.jpg))