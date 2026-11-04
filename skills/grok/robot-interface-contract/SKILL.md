---
name: Robot interface contract
description: >-
  Use when defining or reviewing subsystem interfaces on Win’s robots (power,
  mechanical mounts, signals, ROS topics/services, timing, ownership).
---
# Robot interface contract

## When
New subsystem, integration meeting, milestone, or “how do these parts talk.”

## Steps
1. Name producer and consumer + owner bot/person.
2. Mechanical: mounts, envelopes, loads, fasteners, keep-outs.
3. Power: voltage, current budget, connectors, ground, protection.
4. Signals: protocol, pinout, levels, isolation.
5. Software: ROS topics/services/actions, message types, QoS, TF frames, rates.
6. Timing/latency and failure modes (what happens if link drops).
7. Acceptance test for the interface alone before full-system test.

## Rules
- Prefer tables over prose.
- Label UNKNOWN rather than inventing pinouts or message fields.
