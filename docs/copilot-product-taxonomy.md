# Copilot Product Taxonomy

> The map. Read this before choosing a track. "Copilot" is a brand stretched across very different products; this document fixes what each one *is*, so a learner never confuses the coding assistant in their IDE with the meeting-recap assistant in Teams.

---

## The three families

Everything in this system falls into one of three families. The family determines the licence, the grounding data, and the mental model.

1. **GitHub family** — Copilot for *building software*. Grounded in your **code and repositories**. Licensed through **GitHub** (per-user or per-seat). Lives in the IDE, on github.com, in the CLI, and — via integration — in Azure DevOps.
2. **Microsoft 365 family** — Copilot for *knowledge work*. Grounded in the **web** and, when licensed, your **work data via Microsoft Graph** (mail, files, chats, meetings). Licensed through **Microsoft 365**. Lives in Word, Excel, PowerPoint, Teams, Outlook, and the Copilot Chat app.
3. **Power Platform family** — Copilot for *making agents*. **Copilot Studio** is the low-code studio where you *build* custom agents that then run inside the Microsoft 365 family or standalone.

The single most important distinction a beginner must internalize: **the GitHub family is grounded in your code; the Microsoft 365 family is grounded in your documents and communications.** They do not share a brain, a licence, or a grounding source.

---

## The distinguishing table

| Track | Family | Primary surface | Grounded in | Licence model | Learner is… | Owns which decision |
|---|---|---|---|---|---|---|
| **GitHub Copilot** | GitHub | VS Code / Visual Studio / JetBrains / CLI | Your repository, open files, selection | GitHub Copilot Free / Pro / Pro+ / Business / Enterprise | A developer or technical contributor | "How do I write, change, and review this code?" |
| **Copilot in Azure DevOps** | GitHub × Azure DevOps | Azure Boards work items, PRs, pipelines | Work items + linked repo context | GitHub Copilot licence surfaced in Azure DevOps | A team delivering via Azure Boards | "How do I plan and shepherd this work item?" |
| **Copilot Chat — Basic** | Microsoft 365 | Copilot Chat app / m365.cloud.microsoft / Edge | **Web only** (no work-data access) | Included with eligible M365 business licences; no add-on | Any employee | "Answer a general question with enterprise data protection." |
| **Copilot Chat — Premium** | Microsoft 365 | Copilot Chat + in-app across M365 | **Your work data** via Microsoft Graph + web | Microsoft 365 Copilot **add-on** licence (paid) | Any licensed employee | "Answer using *my* files, mail, chats, and meetings." |
| **Copilot Studio** | Power Platform | Copilot Studio maker portal | Whatever data sources *you* connect | Copilot Studio licensing / capacity packs | A maker / citizen developer | "How do I *build* an agent others will use?" |
| **Copilot in Excel** | Microsoft 365 | Excel (requires M365 Copilot licence) | The active workbook + Graph | Microsoft 365 Copilot add-on | An analyst / spreadsheet user | "Analyze, formula, and surface insight in this sheet." |
| **Copilot in Word** | Microsoft 365 | Word (requires M365 Copilot licence) | The active document + Graph | Microsoft 365 Copilot add-on | A writer / document author | "Draft, rewrite, and summarize this document." |
| **Copilot in PowerPoint** | Microsoft 365 | PowerPoint (requires M365 Copilot licence) | The active deck + Graph | Microsoft 365 Copilot add-on | A presenter | "Build and refine this deck." |
| **Copilot in Teams** | Microsoft 365 | Teams meetings & chat (requires M365 Copilot licence) | Meeting transcript, chat history + Graph | Microsoft 365 Copilot add-on | A meeting participant | "Recap, catch up, and capture actions." |

---

## Reading the Chat Basic vs. Premium split

JMS's track list names **Copilot Chat Basic** and **Copilot Chat Premium**. In Microsoft's current naming these map cleanly:

- **Copilot Chat — Basic** = **Microsoft 365 Copilot Chat** included at no extra cost with eligible business licences. It is grounded on the **web**, protected by **enterprise data protection**, and can run **pay-as-you-go agents** — but it **cannot see your organizational data**.
- **Copilot Chat — Premium** = the paid **Microsoft 365 Copilot** add-on. It adds **work-data grounding through Microsoft Graph** (your files, emails, chats, people, meetings), **in-app Copilot** across Word/Excel/PowerPoint/Outlook/Teams, and advanced agents (e.g. Researcher, Analyst).

The boundary between them is exactly **"can it see my work data?"** Basic cannot; Premium can. Everything else — in-app assistants, meeting recap, the advanced agents — rides on the Premium licence. *(Naming and inclusions are Microsoft's as of July 2026 and change often; verify against the Microsoft 365 Copilot service description before quoting to a client.)*

---

## Which track should a learner start with?

- **A developer** → **GitHub Copilot**. If the team plans in Azure Boards, add **Copilot in Azure DevOps** next.
- **Any employee, no add-on licence** → **Copilot Chat — Basic**. It is the safe, universal on-ramp.
- **A licensed knowledge worker** → **Copilot Chat — Premium**, then the in-app tracks (**Word / Excel / PowerPoint / Teams**) for the apps they live in.
- **A maker who wants to build reusable agents** → **Copilot Studio** (after they are comfortable *using* Copilot Chat — Premium).

---

## The one rule that spans every family

Whatever the surface, the human is the author and the reviewer. Copilot proposes; you verify against the real source, and you ship. This is the first lesson of every track's **Mindset** thread — see the [Level Model](level-model.md).

---

## Sources

- [What's the difference between Microsoft Copilot (free) and Copilot in Microsoft 365 — Microsoft Support](https://support.microsoft.com/en-us/microsoft-365-copilot/what-s-the-difference-between-microsoft-copilot-free-and-copilot-in-microsoft-365)
- [What is Microsoft 365 Copilot? — Microsoft Learn](https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-overview)
- [Plans for GitHub Copilot — GitHub Docs](https://docs.github.com/en/copilot/get-started/plans)
- [Use GitHub Copilot with Azure Boards — Microsoft Learn](https://learn.microsoft.com/en-us/azure/devops/boards/github/work-item-integration-github-copilot)
- [Microsoft Copilot Studio documentation — Microsoft Learn](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)

*Copilot Product Taxonomy v1.0 — July 2026*
