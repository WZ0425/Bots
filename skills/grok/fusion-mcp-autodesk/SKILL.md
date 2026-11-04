---
name: fusion-mcp-autodesk
description: >-
  Drive a live Autodesk Fusion desktop session through Autodesk's official
  Fusion MCP (execute/read/update). Use when modeling or editing in Fusion via
  MCP on the PC where Fusion is open.
---
# Autodesk Fusion MCP (official)

## Preconditions
1. Fusion desktop running with a design open.
2. Preferences → General → API → Fusion MCP Server on; Cursor MCP URL matches the live link (often `http://127.0.0.1:<port>/mcp`).
3. Agent on that same PC (Cursor IDE / My Machines). Stock cloud VMs cannot reach localhost Fusion. Grok Bot box cannot either — guide Win or use STEP via text-to-cad.

## Tools
- `fusion_mcp_read` — screenshot / docs / design info (start every session)
- `fusion_mcp_execute` — Fusion Python (adsk.core / adsk.fusion)
- `fusion_mcp_update` — undo/redo
- `fusion_mcp_electronics_read` — optional electronics preview

Do not invent third-party tools (`draw_rectangle`, …) unless listed in-session.

## Protocol
1. List tools → read/screenshot → confirm design.
2. Talk mm to Win; convert in script to document units.
3. Small smoke change first; re-read after each modify (indices stale).
4. Export ≠ save `.f3d` — ask Win to File → Save.
5. Keep bodies separate until Win confirms join/cut.

## Paths
Live Fusion → this skill. New STEP/STL offline → text-to-cad `cad`. Owner for robot hardware CAD: Work · Mechatronics.
