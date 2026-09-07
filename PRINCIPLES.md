# Principles · หลักการ

How a future reader reconstructs the work **without private source**.

English is primary. Thai is welcome in the headings because the studio is bilingual on purpose — not as decoration.

---

## 0 · What you are reconstructing

Not a vendor catalogue. A **civic studio** grown from a city-reporter bot (2024) into a public GitHub account of 100+ repositories (2026). The running systems that hold other people's data stay private. The *way they were thought* was published.

If you only clone private repos you do not have, you will learn nothing. If you read the five public blueprints, fork one tower, and keep the ranking honest, you can rebuild the method.

A shorter teaching door — who this is for, a six-repo path, ethical fork — is **[START-HERE.md](START-HERE.md)**.

---

## 1 · Public blueprints first

These five are the reconstruct kit. They are public. They are enough.

| Gift | Repo | What it gives you |
|---|---|---|
| Flood system as ideas | [`FloodDash-Blueprint`](https://github.com/Nonarkara/FloodDash-Blueprint) | Architecture, free Thai and international data sources, the science, design language, a phased roadmap. **Deliberately no live source code.** Live system: [flood.nonarkara.org](https://flood.nonarkara.org) (implementation private). |
| Satellite dashboards | [`DrNon-Global-Satellite-Toolkit`](https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit) | Clone → pick a geography → deploy. Pluggable modules, deck.gl, fallbacks. |
| Ranking without a black box | [`SLIC-Index`](https://github.com/Nonarkara/SLIC-Index) | V3 only. Every score traceable. Archives exist; they are not the kit. |
| How the dashboards get built | [`live-coding-bible`](https://github.com/Nonarkara/live-coding-bible) | Tactics already used in production: correlate unlike sources, pretend-real-time via honest cadence, satellite-first pages, graceful degradation. |
| How the studio ships with agents | [`dr-non-vibecoding-skills`](https://github.com/Nonarkara/dr-non-vibecoding-skills) | Skills and playbooks in markdown. No runtime. Loads in whatever agent reads files. |

The GitHub description of `dr-non-vibecoding-skills` (quoted, not re-measured here):

> 31 skills + 10 playbooks, distilled from 1,691 commits and 110 always-on services. The system I use every day to ship real software alone with AI agents — memory ladder, deploy discipline, design DNA, 3D city maps, local AI + voice cloning. Plain markdown, no runtime; loads in Claude Code, Antigravity, Codex, Cursor, Gemini CLI, Aider, OpenCode.

Treat those counts as **his claim in that description**. This history does not audit them.

---

## 2 · The one-Mac thesis

FloodDash is a 24/7 Thailand flood system **on one Mac**. The agentic council repo describes a nine-bot team that “runs on a Mac.” The vibecoding-skills description, again as a claim, speaks of always-on services off one machine.

Reconstruction rule: **prefer a laptop you can restart over a platform you cannot explain.** CDN on the front, a machine you own on the back, mocks when the laptop sleeps. The live-coding bible names this split; the FloodDash blueprint invites you to build your own without waiting for our hardware.

You do not need our Mac. You need our stubbornness about owning the runtime.

---

## 3 · Fork-a-city control towers

Municipal dashboards in this studio share one grammar:

**React + deck.gl + Hono + Cloudflare**

Public exemplar: [`nst-control-tower`](https://github.com/Nonarkara/nst-control-tower) — Nakhon Si Thammarat, flood-first, because flooding is that city's defining risk.

The public Phuket dashboard README states it was retargeted from the geopolitics dashboard. Geography is a parameter. Honesty about sources is not.

Private towers (chula, yala, kmitl, praram9, lopburi, sikhio, chonburi) are the same idea pointed at other places. You do not need them. Fork NST (or city-hub, or the satellite toolkit), bind **your** rivers, **your** AQI, **your** civic inbox. Label modelled numbers as modelled.

Control tower ≠ SLIC. A tower answers *what is happening tonight, where do I send help?* SLIC answers *what kind of city is this, and who is lying about it?* Keep the objects separate. Diagram: [`artifacts/grammar.md`](artifacts/grammar.md).

---

## 4 · Bilingual · สองภาษา

Thai is not a locale file bolted on at the end. FloodDash-Blueprint is TH/EN by design. SLIC's public README claims multilingual copy. `mean` is a hundred words across three languages. NST ships a Thai README. These history pages keep English as the reconstructable spine and let Thai sit in titles where it is natural.

If you rebuild a Thai city system in English-only, you have not rebuilt it. If you rebuild it in Thai-only, you have shut the door this studio leaves open.

---

## 5 · No black boxes on rankings

SLIC's public argument is the sentence on V2's archive description:

> Every city ranking is a lie. Here's ours.

V3's GitHub description insists on traceable scores, no paywall, no black box. The recovered V1 archive description: *one declared formula, zero black boxes.*

Reconstruction rule: **if a number cannot be walked backwards to a source and a weight, it does not ship.** That applies to city ranks, flood watch scores, and air-quality “cigarette equivalents.” Publish the formula. Put war zones on a watchlist instead of dropping them. When you archive a version, leave the URL and mark it archived — as this account did on 2026-08-31 — rather than pretending V3 was always the only file.

Do not fork V1/V2/V2.5/recovered/landing as your starting ranking. They are **archived**. Fork [`SLIC-Index`](https://github.com/Nonarkara/SLIC-Index).

---

## 6 · Gift vs system

| | Public | Private |
|---|---|---|
| Flood | `FloodDash-Blueprint` | `FloodDash` (runs at flood.nonarkara.org) |
| Finance | `ikigai-finance` (OSS cockpit) | `ikigai-dashboard` (PII-adjacent SME cockpit) |
| Bangkok atlas | `BKKx`, `BKKxCulture` | `bkk-3d-atlas` |
| Brain | `second-brain-os` | `second-brain-vault` |
| Origin | this story | `city-reporter-bot` and siblings |

The gift is how you learn. The system is how a city is served today. Confusing them is how people demand source they should not have, or ignore blueprints they should fork.

---

## 7 · What not to reconstruct from

- **Archived landing pages** (`non-landing-page` … `-5`). They are how identity was sketched, not how the site should be forked. Use [nonarkara.org](https://nonarkara.org).
- **Forks of other people's platforms** (`supabase`, `freellmapi`). They are not the studio's thesis.
- **Star counts.** The CSV records GitHub's field. Most public repos had zero at snapshot. That is not a quality score.
- **Private internals.** If a line is not a purpose, it should not appear in a memoir.

---

## 8 · A working evening (suggested)

1. Read this file and [ORIGIN.md](ORIGIN.md).
2. Skim [`live-coding-bible`](https://github.com/Nonarkara/live-coding-bible).
3. Open [`FloodDash-Blueprint`](https://github.com/Nonarkara/FloodDash-Blueprint) and [`SLIC-Index`](https://github.com/Nonarkara/SLIC-Index) in the browser (V3 live: [GitHub Pages](https://nonarkara.github.io/SLIC-Index/)).
4. Fork [`nst-control-tower`](https://github.com/Nonarkara/nst-control-tower) **or** [`DrNon-Global-Satellite-Toolkit`](https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit).
5. Point it at **one** geography you actually know. Wire **two** unlike open data sources on the same map. Label uncertainty.
6. Write the formula down before you write the legend.

If that evening produces something a neighbour could use in a flood or a dust season, the studio reproduced. If it produces a slide, start again from the reporter: one issue, one place, one source you can name.

— Dr Non · [github.com/Nonarkara](https://github.com/Nonarkara) · [nonarkara.org](https://nonarkara.org)
