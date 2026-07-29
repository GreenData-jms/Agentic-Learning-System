# 01 — Mindset (how to think)

The Mindset thread is the judgment that makes speed safe. Tools change weekly; these habits don't.

---

## Mate · Beginner — Author-in-the-loop

**The core stance.** Copilot proposes; you dispose. Every suggestion is a draft written by a confident, fast, sometimes-wrong colleague. Your job is not to type less — it is to *decide* well.

- **Read every suggestion before accepting it.** If you don't understand it, don't take it.
- **Know what it's good at.** GitHub's own guidance: Copilot shines on boilerplate, repetitive patterns, tests, and "I know what I want but forget the syntax" moments. It struggles with novel logic, your codebase's implicit conventions, and anything requiring information it can't see.
- **Name one thing you won't trust it with.** Auth logic? A migration? A regex on money? Good — that instinct is the lesson.

**Beginner is done when** you can accept a suggestion, explain *why* it's correct, and point to one class of task you'd write yourself.

---

## Mate · Intermediate — Trust calibration

Calibrate how hard you check against how much the code matters. Low-stakes scaffolding: a glance. A payment path, a security boundary, a data migration: full review, plus a test.

- **Verify before you commit — always.** Run it. Test it. Read the diff. Copilot can produce code that compiles and is still wrong.
- **Watch for confident nonsense.** Invented APIs, plausible-but-wrong parameters, subtle off-by-ones. The more fluent the output, the more deliberately you should check.
- **Know when *not* to use it.** When you don't yet understand the problem yourself, reaching for Copilot skips the thinking that makes the review meaningful. Understand first, then accelerate.

**Intermediate is done when** your verification effort visibly scales with stakes, and you can cite a time you rejected a suggestion that looked right.

---

## Mate · Advanced — Governance, security & data instincts

At this band you think about the code *and* the system around it.

- **Security review is yours, not Copilot's.** Treat generated code as untrusted input: check for injection, secrets, unsafe deserialization, and dependency risk. Copilot can *help* review (see Toolset), but accountability stays with you.
- **Data & context hygiene.** Understand what Copilot sends as context and configure **content exclusion** so sensitive files never leave. Know your org's policy.
- **Licensing & provenance.** Enable the duplication-detection filter where required; understand your org's stance on suggestions that match public code.
- **Model choice is a decision.** Default models are fast and cheap; premium models cost credits and suit harder reasoning. Spend deliberately.

**Advanced is done when** you can walk a Beginner through the author-in-the-loop rule *and* explain your org's content-exclusion and review posture.

---

*GitHub Copilot Track — Mindset v1.0 — July 2026*
