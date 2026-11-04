---
name: Robot wiring bring-up
description: >-
  Use when planning power/signal wiring, battery/motor-driver hookup, or
  first-power bring-up for Win’s robots.
---
# Robot wiring bring-up

## When
New harness, battery change, motor driver, sensor bus, or first power-on.

## Steps
1. Block diagram: battery → protection → regulators → loads; separate power vs signal grounds in guidance.
2. Connector pinout table; wire gauge and fuse/breaker notes.
3. EMI/noise basics (twisted pairs, return paths) when motors + sensors share a platform.
4. Bring-up order: unpowered continuity → limited current first power → logic → actuators unloaded → loaded.
5. Abort checklist (smoke, undervoltage, runaway).
6. Prefer COTS modules unless PCB-level is requested.

## Rules
- Label UNKNOWN pins; never invent undocumented pinouts.
