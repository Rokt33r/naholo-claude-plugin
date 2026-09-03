---
name: audit-rule
description: Audit a skill markdown against the route-step/act-step format. Classifies each step, checks route syntax and mutual exclusivity, tightens act steps to one instruction per line, strips no-ops; flags riskier cuts for review. Pass a skill name or a path to the markdown file.
argument-hint: '<skill-name | path-to-markdown>'
---

Run `naholo agent skills audit-rule` and follow stdout.

If `naholo` is not found or the command errors, tell the user to run `/naholo-doctor` to diagnose and fix the CLI setup, then stop.
