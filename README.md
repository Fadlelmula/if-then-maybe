# if-then-maybe

> A high-entropy sandbox for small code experiments, system tests, and the occasional human-shaped edge case.

*In folklore, the red spider lily blooms where paths diverge one flower, no leaves, growing right on the boundary between what was and what's next. Fitting company for a repo that lives entirely on that line.*

---

## `01_manifesto.md`

Most repositories are built to prove something. This one is built to *find out* something.

`if-then-maybe` is where hypotheses go before they're allowed to call themselves projects. Some of what's here will compile and mean nothing. Some of it will break and mean everything. The branch condition is rarely clean — that's the point.

```
while (curious) {
    try_something();
    if (works) log("interesting");
    else       log("also interesting");
}
```

---

## What lives here

- 🧪 **Experiments** — small, self-contained, disposable by design
- 🔍 **System tests** — probing how things actually behave vs. how the docs say they behave
- 🧩 **Edge cases** — the inputs nobody accounted for, including the human ones
- 📓 **Notes-in-code** — learning captured as working examples, not just comments

Nothing here is production-grade. That's not a disclaimer — it's the operating mode.

---

## Philosophy

```
Learn → Build → Document → Improve → Share
```

Each folder is a checkpoint, not a monument. If something here looks unfinished, it probably is check back later, or don't; entropy doesn't owe you closure.

---

## Structure

```
if-then-maybe/
├── experiments/     # small, self-contained questions in code
├── prototypes/      # experiments growing into something more substantial
├── notes/           # observations, learning logs, and decisions
└── assets/          # images or files used by experiments
```

*(structure will drift as the entropy does)*

---

## A running hypothesis

> Most bugs aren't failures of logic. They're failures of assumption.

This repo is, in part, an attempt to collect enough assumptions in one place to start seeing the pattern.

---

## Status

`condition: unstable`
`branches: many`
`regrets: version-controlled`

---

*🔴 One flower. No leaves. Blooms anyway.*

<sub>Part of a larger build — see [github.com/Fadlelmula](https://github.com/Fadlelmula) for the rest of the plot.</sub>
