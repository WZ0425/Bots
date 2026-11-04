---
name: fusion-cad-handoff
description: >-
  Choose between live Fusion MCP vs parametric build123d/text-to-cad for a CAD
  ask. Use when the user wants a part, tray, mount, enclosure, STEP/STL, or
  Fusion edit.
---
# Fusion vs CAD path

| Need | Path |
| --- | --- |
| Edit open Fusion design now | `fusion-mcp-autodesk` on Win’s PC Cursor Agent |
| New parametric STEP/STL/3MF | text-to-cad `cad` (build123d) |
| COTS STEP | text-to-cad `step-parts` |
| Drawing / DXF / DFM | text-to-cad engineering-drawing / dxf / dfm / dfam-check |
| Stock Cursor cloud VM | Cannot hit localhost Fusion |

Talk mm to Win; don’t claim Fusion changed without MCP confirmation.
