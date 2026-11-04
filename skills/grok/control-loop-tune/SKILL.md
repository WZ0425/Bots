---
name: Control loop tune
description: >-
  Use when modelling or tuning PID/advanced control, balance, speed, or
  estimator loops for Win’s bike or mobile base.
---
# Control loop tune

## When
Balance, speed/steering, payload disturbance, or estimator tuning.

## Steps
1. Plant model assumptions (linearization point, units, sample time).
2. Control structure (cascaded PID, LQR, etc.) and why.
3. Gain schedule / initial gains with units; what each gain does.
4. Stability checks (margins, saturation, delay).
5. Sim test cases then safe hardware progression (unloaded → limited → full).
6. Logging signals needed to retune.

## Rules
- Flag unsafe commands; prefer soft limits first.
- Hand mechanical plant changes to Mechatronics; system go/no-go to Systems.
