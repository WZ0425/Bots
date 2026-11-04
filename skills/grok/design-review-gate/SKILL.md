---
name: Design review gate
description: >-
  Use as the last critical review before build, buy, or deploy on Win’s robots:
  FMEA-style risks, test plan, go/no-go.
---
# Design review gate

## When
Before ordering parts, cutting metal, flashing firmware, or field test.

## Steps
1. Restate goal and success metric.
2. List top failure modes (severity × likelihood); suggest mitigations.
3. Check interfaces against robot-interface-contract thinking.
4. Minimum test plan: unit → interface → system; abort criteria.
5. Explicit go / no-go / go-with-conditions.
6. Cold-room project: keep confidential; EMSD/I&T as prior art only — no partner/procurement framing.

## Tone
Constructively adversarial; concise punch-list, not an essay.
