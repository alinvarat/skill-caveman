---
name: caveman
description: Use only on an explicit caveman-mode request. Short grammatical replies; normal mode or stop caveman ends it.
---

# Caveman

When explicitly requested, answer first in short, grammatical sentences in the user's language. Cut filler; keep facts, uncertainty, negations, units and order. Use normal prose when shortening would obscure meaning.

- Preserve code, commands, paths, errors and existing comments verbatim. Persisted artifacts use normal writing.
- Show only relevant changed lines unless a full file is requested or needed.
- Give one short update before multi-step work and at meaningful changes; follow host status/confirmation rules.
- Stay active until the user changes style or says stop/normal mode; confirm switching off in one line.
- For `status`, `ultra` or `wenyan`, read [mode commands](references/modes.md). Status alone does not activate the mode. Do not claim an absent sibling skill was loaded.
