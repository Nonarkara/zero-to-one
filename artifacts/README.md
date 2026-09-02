# Artifacts

Lightweight files generated **in this repository**. Nothing here is a copy of another project's git history, source tree, or binary assets.

Learners should start at [`START-HERE.md`](../START-HERE.md) — who the history is for, a teaching mermaid of the 2026 civic estate, an ordered six-repo path, and how to fork ethically.

The README hero lives at [`docs/hero-banner.png`](../docs/hero-banner.png). It is an **illustration** — the golden HUD, polaroids, and sticky notes are drawn in the picture, not generated as a live overlay.

| File | What it is |
|---|---|
| [`public-repos.csv`](public-repos.csv) | Every **public** repo visible on `users/Nonarkara/repos` on **2026-08-31**, with GitHub `created_at`, `description`, `html_url`, archive/fork flags, language, homepage field, and `stargazers_count` as GitHub returned them. |
| [`github-user.json`](github-user.json) | Public profile fields for [`Nonarkara`](https://github.com/Nonarkara). |
| [`studio-clusters.svg`](studio-clusters.svg) | Hand-written map of the studio's clusters (public vs private vs archive). |
| [`slic-lineage.md`](slic-lineage.md) | Mermaid: SLIC V1 → V3 and the 2026-08-31 archive. |
| [`from-bot-to-studio.md`](from-bot-to-studio.md) | Mermaid: city-reporter seed → public studio. |
| [`grammar.md`](grammar.md) | Mermaid: the municipal dashboard grammar vs the ranking that disagrees. |

## How to refresh the CSV

Do **not** clone the studio. Ask GitHub:

```bash
gh api "users/Nonarkara/repos?per_page=100&type=owner" --paginate > /tmp/nonarkara-repos.json
```

Then rebuild the CSV from that JSON. Private repos will not appear. That is the point.

Star counts in the CSV are GitHub's field at snapshot time, not a ranking of the work. Most public repos had zero stars when this file was written. Do not turn that column into a story.
