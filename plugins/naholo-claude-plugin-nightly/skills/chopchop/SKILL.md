---
name: chopchop
description: Apply the CHOP proposal — runs a pre-flight validation against the parent, allocates TRP into `CHOP.md` per side, then shells out to `naholo agent chopchop` which spawns the new OP, prunes the parent, posts a seed log, pushes, and cleans up. Run after `/chop` produces `notes/CHOP.md` and the user has reviewed it.
argument-hint: ''
---

Run `naholo agent skills chopchop --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
