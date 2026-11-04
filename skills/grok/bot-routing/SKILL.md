---
name: bot-routing
description: >-
  Use when assigning work across Win’s Grok Bots after the 2026-11-04
  Poteto-style roster: which bot owns study, work, Canva, GPAI, Stock, cloud
  agents, or oversight.
---
# Bot routing (Poteto-optimized roster)

## Usage rule (default)
**Rooms first, specialists second.** Prefer one room thread over waking 2+ specialists. Wake a specialist only when the job is clearly theirs alone.

## Active bots
- **Main · Chief of Staff** — front door; route and bridge; do not redo owned specialty work.
- **Study Coach** — civil theory, worked problems, quizzes/exams/flashcards.
- **Study Ops** — weekly timetable, assignment/lab brief structure, civil research packs; no submit-ready ghostwriting.
- **Study · Scribe** — first drafts of lab/academic reports from Win’s notes/data (Google Docs preferred); Win reviews before submit.
- **Work · Systems** — requirements, architecture, milestones, risks, FMEA/critical review.
- **Work · Mechatronics** — mechanical, electronics, firmware.
- **Work · Autonomy** — ROS 2 / software, controls, estimation.
- **Work · R&D** — concepts, prior art, sourced research packs.
- **Canva** — all Canva / PPT slide work.
- **GPAI** — all gpai.app work (prefer Claude Opus 5.5 in chat).
- **Stock** — all Futu; confirm every trade with Win.
- **Cursor · Cloud Agent Orchestrator** — complex/repo cloud agent jobs.
- **Monitor** — live oversight / token-waste checks when asked; keep even with healthcheck routines.
- **News** — morning brief + breakthrough alerts.
- **dr eggbot** — design/create new bots only; not a domain owner.

## Rooms
- **Study — Desk** — Coach + Ops (+ Scribe when drafting) alignment (week plan, tonight’s study block).
- **Work — Robotics** — Systems + Mechatronics + Autonomy alignment (build).
- **Work — Research & Review** — R&D + Systems alignment (prior art / go-no-go).

## Solo wakes (only when the job is clearly one lane)
- drills/theory/exams → Study Coach
- timetable / lab outline / research pack → Study Ops
- **lab/academic report first draft → Study · Scribe** (not Ops, not cloud agents unless LaTeX repo)
- plan/FMEA/milestones → Work · Systems
- CAD/wiring/MCU → Work · Mechatronics
- ROS/controls → Work · Autonomy
- cheapest test / prior art → Work · R&D
- complex repo coding → Cursor Orchestrator (never Autonomy typing a whole stack in chat)
- slides → Canva; gpai.app → GPAI; Futu → Stock

## Never route new work to
- Any **Archive · …** bot
- **Study — Civil** (legacy shell — delete from sidebar if still present)

## Skills over new bots
If a workflow repeats twice, save a skill instead of creating another bot. Use dr eggbot only for a genuinely new strong job.
