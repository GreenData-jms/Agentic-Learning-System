# 04 — Labs

Hands-on work, tagged by band. Use a **real repository you can safely experiment in** — a scratch clone, not production. Every lab ends the same way: *verify the result.*

---

## Beginner labs

**B1 — First light.** Install the extensions, sign in, open a repo. Write a comment describing a small pure function (e.g. "return the median of a list of numbers"). Accept the completion, then write a test that proves it right. *Done when the test passes and you can explain the code line by line.*

**B2 — Reject on purpose.** Prompt for something slightly ambiguous. Get a suggestion that looks plausible but is subtly wrong; identify why; reject it. *Done when you can articulate the flaw.*

**B3 — Ask mode.** Open Copilot Chat, ask it to `/explain` a file you didn't write. *Done when you can summarize the file in two sentences.*

---

## Intermediate labs

**I1 — Mode routing.** Take one task and do it three ways: *Ask* to understand, *Edit* to make the change, *Agent* to do a multi-step version. Note which fit. *Done when you can say which mode you'd default to and why.*

**I2 — Context steering.** Make the same edit twice — once with no files attached, once with the right `#file`/`#selection` context. Compare quality. *Done when you can show the difference context made.*

**I3 — Test-first with `/tests`.** Pick an untested function; generate tests with `/tests`; run them; fix any real gaps. *Done when coverage is real, not just green.*

---

## Advanced labs

**A1 — Custom instructions.** Write `.github/copilot-instructions.md` for your repo (stack, conventions, don'ts). Re-run an earlier task and observe the difference. *Done when suggestions visibly follow your conventions unprompted.*

**A2 — Prompt file.** Capture a repeatable task as a `*.prompt.md`; invoke it twice on different inputs. *Done when a teammate could run it and get consistent output.*

**A3 — Copilot code review.** Open a PR; request a Copilot review; act on the useful findings; note the noise. *Done when you can judge where AI review helps and where it doesn't.*

**A4 — Coding agent.** Assign a small, well-scoped issue to Copilot; review the PR it opens as rigorously as a human's. *Done when you've either merged it after real review or sent it back with specific changes.*

**A5 — Mentor.** Walk a Beginner through B1. *Done when they ship a verified result and can state the author-in-the-loop rule.*

*GitHub Copilot Track — Labs v1.0 — July 2026*
