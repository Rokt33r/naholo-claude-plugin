---
name: replan
description: Apply a combined ADR + TASKS revision in one pass by chaining /adr then /task with the same prompt. Use when a change touches both the ADR and the task list.
argument-hint: '["revision prompt"]'
---

Run `naholo agent skills replan --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
