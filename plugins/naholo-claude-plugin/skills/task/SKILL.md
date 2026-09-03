---
name: task
description: Cut an adr'd Naholo issue's ADR into single-commit-sized tasks. Write TASKS in PLAN.md, mirror to TASKS.md.
argument-hint: '["freeform plan-revision instructions"]'
---

Run `naholo agent skills task` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
