# AGENTS.md

## Project

This repository is the shareable Grok Bot and Cursor setup pack: Cursor rules, a coding-repo `AGENTS.md` template, sanitized skill copies, and short docs. It is not a product codebase. Update it with small, readable diffs. Runtime skills on the bot computer, and large third-party skills on the PC, stay where they already live.

## How to update the pack

1. Restate what changed (a rule, a skill recipe, the roster, or a doc link) and name a check that can pass or fail: the tree still matches `README.md`, and a scan of the diff finds no tokens, account ids, emails, or vault data.
2. Edit the matching path (`rules/`, `templates/`, `skills/grok/<id>/`, or `docs/`). When a Grok skill name is new, add it to `skills/grok-skill-index.txt`, and add a short `SKILL.md` only when the recipe is ours to share.
3. Keep each pull request to one concern.
4. Bike verification and statechart code stays in `WZ0425/Autonomous-Bike-lmbike-`. Link it from `docs/links.md`.

## Keep PRs small

One topic per PR. Leave Graphify, Anthropic skill packs, and plugin caches on the PC under `~/.cursor/skills`. Do not dump third-party trees into this repo.

## Never commit secrets

No tokens, API keys, vault exports, course UIDs, brokerage account numbers, or personal contact details. If a skill needs an account id, point at local bot config and leave the value out.
