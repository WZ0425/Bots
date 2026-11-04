# Bots — Grok Bot + Cursor setups

Shareable backup of Win’s Grok Bot roster, Cursor rules, and skill recipes. The live Grok workflows stay on the bot computer; this repo is the pack you copy from.

**No secrets.** Do not commit tokens, vault data, course UIDs, brokerage account ids, or personal contact details.

## Layout

- `rules/` — always-apply Cursor rules (`poteto-habits.mdc`, `pstack-models.mdc`)
- `templates/` — reusable files, including `AGENTS.md` for coding repos
- `skills/` — sanitized Grok skill copies under `skills/grok/<id>/`, plus a name index
- `docs/` — roster, install checklist, and links to work that lives elsewhere
- `AGENTS.md` — how to update this meta-repo

`skills/grok-skill-index.txt` lists workflow names. Only the recipes under `skills/grok/` are stored here.

## Install

### Cursor rules (owner PC)

Copy the rule files into the user rules directory. They are `alwaysApply`.

```bash
mkdir -p ~/.cursor/rules
cp rules/*.mdc ~/.cursor/rules/
```

On Windows that directory is `%USERPROFILE%\.cursor\rules`.

### Coding repos

Copy the template into each coding repo and fill in the Project section for that repo:

```bash
cp templates/AGENTS.md /path/to/coding-repo/AGENTS.md
```

Bike verification and statechart product code stays in the Autonomous-Bike repo. This pack only links to it. See `docs/links.md`.
