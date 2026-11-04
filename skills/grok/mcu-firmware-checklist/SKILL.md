---
name: MCU firmware checklist
description: >-
  Use when scoping microcontroller firmware, bus bring-up (I2C/SPI/UART/CAN), or
  HW-SW debug on Win’s robots.
---
# MCU firmware checklist

## When
MCU node, real-time I/O, bus debug, or firmware sketch before Pi/ROS ownership.

## Steps
1. Role of the MCU vs Raspberry Pi (what must be real-time).
2. Pin/bus map; clocking; power domain.
3. Task loop vs interrupts; timing budget.
4. Protocol choice and failure handling (timeouts, CRC).
5. How to flash, log, and test with actuators disconnected first.
6. Hand-off contract to ROS/Autonomy (topics, rates, units).

## Rules
- Prefer simple bare-metal or well-known frameworks Win can maintain.
- Do not invent register maps; cite datasheet sections to verify.
