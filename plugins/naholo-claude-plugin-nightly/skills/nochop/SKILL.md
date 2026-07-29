---
name: nochop
description: Discard the in-flight CHOP proposal. Deletes `notes/CHOP.md` from both the local infilled dir and the parent OP server-side, stamps TIMELINE, and points the user at the next action based on the parent's `OPERATION.md` state. The parent OP's WARNING ORDER/OPERATION ORDER are not modified.
argument-hint: ''
---

Run `naholo agent skills nochop --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
