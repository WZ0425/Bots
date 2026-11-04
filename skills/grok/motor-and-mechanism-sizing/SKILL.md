---
name: Motor and mechanism sizing
description: >-
  Use when sizing motors, actuators, gears, or mechanisms for Win’s robots with
  free-body, torque/speed, and DFM sanity checks.
---
# Motor and mechanism sizing

## When
Need torque/speed, gear ratio, linkage, wheel, lift, or gripper sizing.

## Steps
1. Free-body / load path; worst-case load and duty cycle.
2. Required torque and speed at the joint/wheel with units; include efficiency and factor of safety explicitly.
3. Propose COTS motor/gear options with margin; note voltage/current draw for power budget.
4. DFM: 3D print / CNC / sheet / student workshop constraints.
5. Sanity check order-of-magnitude; list ASSUMPTIONS.
6. For CAD export / parametric parts, prefer text-to-cad skill pack when appropriate.

## Rules
- Show working; no naked “use a NEMA 17” without numbers.
