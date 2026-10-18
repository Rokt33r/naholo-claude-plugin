---
name: task
description: "Cut the active nightly issue's ADR into single-commit-sized task rows on the server, or revise the unfinished ones."
argument-hint: '["freeform plan-revision instructions"]'
---

Run `naholo agent skills task --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
