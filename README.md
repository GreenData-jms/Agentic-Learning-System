# Agentic Learning System

A structured, track-based curriculum for building fluency with the Microsoft and GitHub **Copilot** family — organized so a learner always knows *which* Copilot they are learning, *why* it is different from its neighbours, and *what* to practise next.

Every track teaches to the same spine — **Mindset → Toolset → Skillset** — across three progression bands inside the entry rank (**Mate**): **Beginner → Intermediate → Advanced**. Learn the frame once, and every new Copilot slots into it.

---

## Why this exists

"Copilot" is not one product. It is a family that spans two platforms (GitHub and Microsoft 365), a low-code agent studio, and a set of in-app assistants — each with its own licence, its own grounding data, its own surface, and its own idea of what "good" looks like. Teaching them as one blurs exactly the distinctions that make a person effective. This system keeps them as **separate tracks** that share a **common learning frame**, so skill compounds instead of colliding.

Start with the [**Copilot Product Taxonomy**](docs/copilot-product-taxonomy.md) — it is the map. Then pick a track.

---

## The three-thread spine

Every track is built from the same three threads. They are not sequential stages; they are parallel strands a learner develops together, deepening band by band.

| Thread | The question it answers | What it builds |
|---|---|---|
| **Mindset** | *How should I think?* | Judgment: when to reach for Copilot, when not to; how to stay the author and reviewer; trust calibration; verification reflex; data and security instincts. |
| **Toolset** | *What do I use?* | Fluency with the actual surfaces, modes, settings, and configuration of the specific Copilot — the buttons, the modes, the files, the switches. |
| **Skillset** | *What can I do — and automate?* | Repeatable technique: prompting patterns, context-shaping, and the workflows a learner builds and automates with the tool. |

Read the full frame, including the definitions of the three bands, in the [**Level Model**](docs/level-model.md).

---

## The rank and its bands

The entry rank across the Agentic Learning System is **Mate**. This whole curriculum lives inside it — a Mate is a capable, safe, productive operator, not yet a specialist or a platform architect. Within Mate there are three bands:

- **Mate · Beginner** — first contact. Set up, produce a first useful result safely, understand what the tool is and is not.
- **Mate · Intermediate** — daily driver. Use the tool fluently in real work, shape context deliberately, apply the core best practices without being told.
- **Mate · Advanced** — power user. Configure and customize the tool, build and automate multi-step workflows, and mentor a Beginner.

Progression between bands is by demonstrated competence, not time served. Each track carries its own checklist.

---

## Track catalogue

Full detail — surface, licence, grounding, and who each is for — is in the [**Copilot Product Taxonomy**](docs/copilot-product-taxonomy.md). Quick map:

| # | Track | Family | One-line distinction | Status |
|---|---|---|---|---|
| 1 | [**GitHub Copilot**](tracks/github-copilot/) | GitHub | The developer's coding assistant in the IDE — completions, chat, edit, and agent mode. | **Complete** |
| 2 | [Copilot in Azure DevOps](tracks/copilot-azure-devops/) | GitHub / Azure DevOps | Copilot brought to Azure Boards work items, PRs, and pipelines. | Scaffold |
| 3 | [Copilot Chat — Basic](tracks/copilot-chat-basic/) | Microsoft 365 | Free, web-grounded chat with enterprise data protection — no work-data access. | Scaffold |
| 4 | [Copilot Chat — Premium](tracks/copilot-chat-premium/) | Microsoft 365 | Licensed Microsoft 365 Copilot — grounded in *your* work data via Microsoft Graph. | Scaffold |
| 5 | [Copilot Studio](tracks/copilot-studio/) | Power Platform | Low-code studio for *building* custom agents, not just using them. | Scaffold |
| 6 | [Copilot in Excel](tracks/copilot-excel/) | Microsoft 365 | Formulas, analysis, and insight over your spreadsheet data. | Scaffold |
| 7 | [Copilot in Word](tracks/copilot-word/) | Microsoft 365 | Drafting, rewriting, and summarizing documents. | Scaffold |
| 8 | [Copilot in PowerPoint](tracks/copilot-powerpoint/) | Microsoft 365 | Deck generation, summarization, and light commanding of slides. | Scaffold |
| 9 | [Copilot in Teams](tracks/copilot-teams/) | Microsoft 365 | Meeting recap, chat catch-up, and action-item capture. | Scaffold |

The **GitHub Copilot** track is fully built out. The remaining tracks ship as **scaffolds**: each has an accurate product distinction, a starter set of official Microsoft/GitHub resources, and the same Mindset/Toolset/Skillset × band skeleton, ready to be filled in.

---

## Repository layout

```
Agentic-Learning-System/
├── README.md                         # You are here
├── docs/
│   ├── copilot-product-taxonomy.md   # The map: every Copilot, distinguished
│   ├── level-model.md                # The Mate rank, the three bands, the three threads
│   └── track-template.md             # The standard skeleton every track follows
└── tracks/
    ├── README.md                     # Track index
    ├── github-copilot/               # ← Complete track
    ├── copilot-azure-devops/
    ├── copilot-chat-basic/
    ├── copilot-chat-premium/
    ├── copilot-studio/
    ├── copilot-excel/
    ├── copilot-word/
    ├── copilot-powerpoint/
    └── copilot-teams/
```

---

## Conventions

- **Boundary.** Content is bounded to official **Microsoft and GitHub** guidance and best practices. Where a claim is time-sensitive (pricing, plan names, preview status), it is dated.
- **Currency.** Copilot ships weekly. Each document carries a version footer; treat anything older than a quarter as due for review.
- **Author-in-the-loop.** Every track teaches the same non-negotiable: the human owns the output. Copilot drafts; you decide, verify, and ship.

---

*Agentic Learning System — Root README v1.0 — July 2026*
