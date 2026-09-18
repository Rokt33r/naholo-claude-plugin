---
name: exfil
description: 'Sync local issue changes back to Naholo and clean up: commits the last shipped task, pushes tasks/notes, drains transcripts, posts a log, optionally closes, and removes the working set (returning to the epic phase inside an epic).'
argument-hint: '["freeform"]'
---

Run `naholo agent skills exfil` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
