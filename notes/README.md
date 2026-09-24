# 📓 notes/

![format](https://img.shields.io/badge/format-mostly%20markdown-informational)
![honesty](https://img.shields.io/badge/honesty-brutal-critical)
![sleep_lost](https://img.shields.io/badge/hours%20lost%20to%20this-uncounted-lightgrey)

> The confession booth of the repo.

Code shows you *what* I built. This folder shows you *why* I thought it would work, and — more often — the exact moment I realized it wouldn't.

## What's in here

```
notes/
├── logs/         # raw, unfiltered "here's what happened" entries
└── decisions/    # the "here's what I concluded and why" writeups
```

## A typical entry looks like this

```markdown
## 2026-09-24 — the reconnect storm

**Assumption:** reconnect logic would just... work.
**Reality:** it worked so well it reconnected 40 times a second.
**Lesson:** exponential backoff exists for a reason. I am the reason.
```

## Why bother writing this stuff down

Because 90% of debugging is just remembering that Past Me already made — and documented — this exact mistake once before. This folder is a mirror, and occasionally a warning label.

## Tags you might spot

`#assumption-was-wrong` `#assumption-was-somehow-right` `#tbh-still-confused` `#solved-at-3am` `#never-solved-abandoned-gracefully`

---

*Every bug is a note that hasn't been written yet.*
