# 02 — Toolset (what to use)

Know the instrument. GitHub Copilot is not one feature but a small kit; fluency is choosing the right piece.

---

## Mate · Beginner — Completions and the primary surface

- **Inline (ghost-text) completions.** As you type, Copilot suggests the next line or block. **Tab** accepts, **Esc** dismisses, **Alt/Option+]** cycles alternatives.
- **Comment-driven completion.** Write a clear comment describing intent; Copilot drafts the implementation beneath it.
- **The Copilot Chat panel.** Open it, ask a plain-language question about the open file, read the answer. That's the whole Beginner surface.

---

## Mate · Intermediate — The three chat modes and context controls

Copilot Chat has three modes. Choosing correctly is the central Intermediate skill.

| Mode | Use it to… | It will… |
|---|---|---|
| **Ask** | Understand code, get explanations, explore options | Answer in chat; change nothing |
| **Edit** | Make a scoped change across the files *you* choose | Propose edits inline for you to review and apply |
| **Agent** | Hand off a multi-step task in the editor | Plan, edit across files, run tools/terminal, and iterate — with your approval |

**Context is everything.** Steer what Copilot sees:

- **`#`-references** — attach specific files, symbols, or the selection (e.g. `#file`, `#selection`).
- **Slash commands** — `/explain`, `/fix`, `/tests`, `/doc` and more for common intents.
- **Selection-scoped chat** — highlight code first so the question is grounded in it.
- **Model picker** — switch models for the task at hand.

---

## Mate · Advanced — Customization, MCP, review, and the coding agent

This is where Copilot becomes *your* Copilot.

- **Custom instructions** — `.github/copilot-instructions.md` in the repo gives Copilot standing context: stack, conventions, do's and don'ts. Path-specific `*.instructions.md` files scope guidance to parts of the tree. This is the single highest-leverage customization.
- **Prompt files** — reusable `*.prompt.md` files capture a repeatable task (e.g. "scaffold a React component to our standard") you can invoke on demand.
- **MCP (Model Context Protocol)** — connect Copilot to external tools and data sources (issue trackers, databases, your own servers) so agent mode can act on real context. Available on all paid plans.
- **Copilot code review** — request an AI review on a PR (or a selection in the editor); tune it with custom instructions so it checks *your* standards.
- **Coding agent** — assign a GitHub issue to Copilot; it works asynchronously on GitHub.com and opens a pull request for you to review. The output is a PR like any other — review it as such.

> **Every Advanced feature still ends at a human review gate.** Customization changes what Copilot *proposes*, never who *approves*.

*GitHub Copilot Track — Toolset v1.0 — July 2026*
