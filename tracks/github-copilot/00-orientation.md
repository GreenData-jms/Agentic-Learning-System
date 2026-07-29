# 00 — Orientation

## What GitHub Copilot is

GitHub Copilot is an AI pair programmer that lives **inside your editor**. It reads the code you have open — the current file, your selection, related files you point it at — and helps you write, change, explain, and review software. It works three ways, escalating in autonomy:

- **Code completion** — ghost-text suggestions as you type.
- **Copilot Chat** — a conversation about your code, with three modes: **Ask**, **Edit**, and **Agent**.
- **Coding agent** — an asynchronous agent on GitHub.com that can take an issue and open a pull request.

It is grounded in **your code**, not your documents or email — that is what separates it from the Microsoft 365 Copilot family (see the [taxonomy](../../docs/copilot-product-taxonomy.md)).

## What it is *not*

- It is **not** a source of truth. It predicts plausible code; plausible is not correct.
- It is **not** a replacement for understanding. If you can't review it, you can't ship it.
- It is **not** aware of anything outside the context it's given — no live web, no private systems, unless you connect them (via MCP, at the Advanced band).

## The plans (as of July 2026 — verify before quoting)

| Plan | Who it's for | Headline |
|---|---|---|
| **Copilot Free** | Trying it out | Limited completions/month, basic chat, auto model selection |
| **Copilot Pro** ($10/mo) | Individual devs | Unlimited completions, chat across IDEs & GitHub, agent capabilities, custom instructions |
| **Copilot Pro+** ($39/mo) | Power users | Higher allowance of premium/AI credits, premium models |
| **Copilot Business** ($19/seat/mo) | Teams | Org policy controls, org-wide custom instructions, broad model catalog |
| **Copilot Enterprise** ($39/seat/mo) | Enterprises | Everything in Business plus priority access and a larger credit pool |

All paid plans include **Model Context Protocol (MCP)**, **custom instructions**, and content-exclusion controls. Premium (non-default) models draw on a monthly **premium-request** allowance. *Plan names, prices, and inclusions change frequently — confirm against [GitHub's plans page](https://docs.github.com/en/copilot/get-started/plans).*

## Setup (VS Code path)

1. Install the **GitHub Copilot** and **GitHub Copilot Chat** extensions.
2. Sign in with your GitHub account and confirm your plan is active.
3. Open a real repository — Copilot is only as good as the context around it.
4. Type a comment describing a small function and watch the ghost text appear. Press **Tab** to accept.

## The one rule to carry into every chapter

**You are the author and the reviewer. Copilot drafts; you decide, verify, and ship.** Every suggestion is a proposal to be read, understood, and tested — never pasted on trust. This is the whole of the [Mindset thread](01-mindset.md), and it is non-negotiable at every band.

*GitHub Copilot Track — Orientation v1.0 — July 2026*
