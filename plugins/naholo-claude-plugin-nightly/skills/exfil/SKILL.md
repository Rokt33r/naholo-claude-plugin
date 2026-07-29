---
name: exfil
description: Sync local operation changes back to Naholo and clean up — pushes tasks/notes, drains transcripts, posts a log, optionally closes, removes the infilled dir.
argument-hint: '["freeform"]'
---

Run `naholo agent skills exfil --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
