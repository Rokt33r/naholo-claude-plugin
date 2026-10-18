---
name: apply-draft
description: 'Apply a DRAFT note on nightly: spawn any chopped issues with their plan data, chain /adr / /task for the parent-side Changes, and mark the note applied.'
argument-hint: '[draft-note-number]'
---

Run `naholo agent skills apply-draft --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
