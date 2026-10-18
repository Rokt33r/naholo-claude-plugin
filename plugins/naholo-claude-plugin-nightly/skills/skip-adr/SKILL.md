---
name: skip-adr
description: 'Fresh-issue shortcut on nightly: write a stub ADR (real Summary + refs, no architectural decisions) and chain `/task` to cut tasks. Use when architecture review is overkill.'
argument-hint: '["freeform task-cutting hints"]'
---

Run `naholo agent skills skip-adr --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
