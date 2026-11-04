# AGENTS.md

## Project
Describe what this repo does in 2–3 sentences (fill per repo).

## How to prove a change
1. Restate the goal and name a check that can pass or fail.
2. Prefer a type, lint, or test over a workaround comment.
3. Keep the change small; prove it with command output, a running app, or a test that failed then passed.
4. Before merge, **agents run the project’s checks** (tests / lint / typecheck / build). Do not treat CI alone as the only gate.
5. The second time the same bug appears, encode a lint/CI rule (or type) — not only a prose note.

## Review style
Prefer empirical runs + formal/deterministic checks over multi-round abstract adversarial review. Skip `/interrogate` unless Win asks. Do not overcook a PR with many abstract review rounds that lack goal context.

## pstack / Cursor
- Hard tasks: `/poteto-mode` when pstack is available.
- First verification skill: `/create-verification-skill` (keep with `/maintain-verification-skill`).
- Stateful systems (ROS modes, MCU FSMs, control loops): `/statechart` + `/create-formal-verification-skill`.
- Knowledge graph (if Graphify installed): `/graphify .` then query before broad exploration.

## Do not
- Invent features or files that are not in this repo.
- Expand scope beyond the asked change.
