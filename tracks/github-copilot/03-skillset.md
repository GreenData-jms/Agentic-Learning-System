# 03 — Skillset (what to do, and automate)

Technique that turns fluency into leverage. Mindset keeps you safe; Toolset gives you the instrument; Skillset is the playing.

---

## Mate · Beginner — A first useful, verified result

1. **Describe intent, then let it draft.** Write a precise comment or docstring; accept the completion; **run and test it**.
2. **Iterate by refining the comment**, not by fighting the suggestion. Vague in, vague out.
3. **Ask chat to explain** anything you accepted but didn't fully follow. Understanding *is* the deliverable at this band.

**Pattern to learn:** *comment → draft → read → test → keep or refine.*

---

## Mate · Intermediate — Prompting patterns and context-shaping

GitHub's prompting guidance, distilled:

- **Set the stage, then be specific.** Open with the goal and constraints; give a concrete example of the input/output you want.
- **Provide references, don't make it guess.** Attach the relevant files/symbols with `#`; keep unrelated files closed so the context stays clean.
- **Break big asks into steps.** One coherent change at a time beats one sprawling prompt.
- **Pick the mode deliberately:** *Ask* to understand, *Edit* for a scoped change you can see, *Agent* for a multi-file task you'll supervise.
- **Use slash commands as accelerators:** `/tests` for a test scaffold, `/fix` on an error, `/explain` on unfamiliar code, `/doc` for docstrings.

**Worked loop:** ask `/explain` on a module → switch to Edit with `#file` attached → request the change with an example → review the diff → `/tests` → run → commit.

---

## Mate · Advanced — Repo-wide changes, automation, and the agent

- **Codify your standards once.** Write `.github/copilot-instructions.md` so every suggestion already knows your stack and conventions — you stop repeating yourself in every prompt.
- **Capture repeatable tasks as prompt files.** Turn "scaffold our standard endpoint / component / test suite" into a `*.prompt.md` the whole team invokes.
- **Automate a real workflow.** Example: a prompt file + custom instructions that takes a bug description, reproduces it with a failing test, proposes a fix, and drafts the PR body — you supervise each gate.
- **Delegate to the coding agent.** For well-scoped issues, assign to Copilot and review the PR it opens. Treat it exactly like a junior teammate's PR: read, test, request changes.
- **Wire in MCP** so agent mode can pull real context (issues, schema, docs) instead of guessing.
- **Mentor.** Teach a Beginner the *comment → draft → verify* loop and the author-in-the-loop rule. Teaching it is how you prove you own it.

**Advanced is done when** you've shipped a reusable, customized workflow others adopt — and brought one person to Beginner.

*GitHub Copilot Track — Skillset v1.0 — July 2026*
