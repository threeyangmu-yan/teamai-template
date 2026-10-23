---
name: demo-github-hello
description: Tiny TeamAI GitHub walkthrough skill — greets and confirms the admin fork→push→PR flow works.
metadata:
  origin: teamai-github-walkthrough
---

# Demo GitHub Hello

A minimal skill used to verify the TeamAI admin flow on GitHub:
fork template → `teamai init` → `teamai push` → open a real PR.

## When to Activate

- Verifying TeamAI GitHub provider setup
- Smoke-testing skill push / PR creation
- Confirming a freshly forked team repo accepts new skills

## What It Does

1. Confirm the workspace is initialized against the user's fork
2. Reply with a short hello that names the skill `demo-github-hello`
3. Point the operator at `teamai status` and the dashboard if they want next steps

## Notes

- Safe / non-destructive demo content only
- Do not modify production configs when this skill alone is active
