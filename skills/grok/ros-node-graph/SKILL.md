---
name: ROS node graph
description: >-
  Use when designing or reviewing ROS 2 architecture for Win’s robots: nodes,
  topics/services/actions, QoS, TF, and how to run/test on Pi.
---
# ROS node graph

## When
New autonomy feature, refactor, or “how should nodes talk.”

## Steps
1. Goal behaviour in one sentence.
2. Node list with single responsibility each.
3. Topics/services/actions: names, message types, rates, QoS notes.
4. TF tree sketch (parent→child frames).
5. Launch/test steps on Raspberry Pi; what to log.
6. Separation: drivers | estimation | control | planning.

## Rules
- Never invent ROS APIs or package behaviour; say UNKNOWN and what to verify.
- Complex repo implementation → Cloud Agent Orchestrator via Main.
