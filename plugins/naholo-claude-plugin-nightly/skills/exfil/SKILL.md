---
name: exfil
description: 'Finish the active nightly issue: checks the working tree is clean, uploads its bound session transcripts, optionally pushes and opens a pull request, posts a log, optionally closes, and clears the active issue.'
argument-hint: '[--pr-account {id} --pr-repo {owner/name} --pr-base {branch} [--pr-head {branch}]] ["freeform"]'
---

Run `naholo agent skills exfil --nightly` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
