# Track Template

Every track in the Agentic Learning System follows this skeleton, so a learner who finishes one track can navigate any other on sight. Copy this structure when building or extending a track.

## Required files

```
tracks/<track-name>/
├── README.md          # Track overview: what this Copilot is, who it's for,
│                      #   the 3×3 matrix, prerequisites, how to use the track
├── 00-orientation.md  # What it is / isn't, licence & setup, first-principles safety
├── 01-mindset.md      # Mindset thread across Beginner / Intermediate / Advanced
├── 02-toolset.md      # Toolset thread across the three bands
├── 03-skillset.md     # Skillset thread across the three bands
├── 04-labs.md         # Hands-on labs, tagged by band
├── 05-assessment.md   # Competency checklist / band advancement criteria
└── references.md      # Official Microsoft / GitHub sources only
```

## Rules for every track

1. **Bounded to official guidance.** Cite Microsoft Learn, GitHub Docs, and the GitHub Blog. No third-party "tips" as primary sources.
2. **Same spine, every track.** Mindset / Toolset / Skillset × Beginner / Intermediate / Advanced. If a cell is genuinely empty for a product, say so explicitly rather than padding.
3. **Author-in-the-loop is chapter zero.** Every track's Mindset thread opens on the human owning the output.
4. **Date the volatile.** Pricing, plan names, preview status, and model names get an as-of date.
5. **Version footer.** `*<Track> Track vN.N — Month Year*` at the foot of the README.

*Track Template v1.0 — July 2026*
