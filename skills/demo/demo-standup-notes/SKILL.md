---
name: demo-standup-notes
description: Draft clear daily standup notes (yesterday / today / blockers) in Chinese or English for eng and product teams.
metadata:
  origin: teamai-github-walkthrough
---

# Demo Standup Notes

Help the user write concise, useful daily standup notes.

## When to Activate

- User asks for standup / 站会 / daily notes
- Preparing a Slack or meeting update of what they did and will do
- Turning rough bullets into a clear yesterday / today / blockers format

## Output Format

```
## Standup — YYYY-MM-DD

**Yesterday / 昨天**
- …

**Today / 今天**
- …

**Blockers / 阻塞**
- None / …
```

## Guidelines

1. Prefer concrete outcomes over vague activity ("merged PR #12" not "worked on auth")
2. Keep each bullet one line; max 3–5 bullets per section
3. Call out blockers early and name who can unblock
4. Match the user's language (中文 or English); bilingual headings are fine
5. If context is thin, ask 1–2 short clarifying questions before drafting

## Notes

- Demo skill for TeamAI push walkthrough — safe / non-destructive
- Do not invent work the user did not mention
