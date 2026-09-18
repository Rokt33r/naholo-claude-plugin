---
name: open
description: Drop an idea, get an issue. Creates a new issue server-side (with an optional first log), attaches it to the infilled epic by default, and chains `/infil` when no issue is active.
argument-hint: '[<title>\n<content lines...>]'
---

Run `naholo agent skills open` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
