# PRINCIPLES

## หลักการ — how to reconstruct this studio from what is public

A future reader should not need private source, client lists, or a tour of anyone's Mac. The method is already published. This page is a reading order and a set of refusals.

**เชิญสร้างต่อ — fork the method, not the secrets.**

---

## 0. Refusals (read these first)

- Do not copy private repositories. If GitHub 404s, that is the answer.
- Do not hunt `.env`, API keys, tokens, webhooks, or subscriber lists. None of that belongs in a reconstruction.
- Do not treat archive repos as the live line. SLIC V3 is [SLIC-Index](https://github.com/Nonarkara/SLIC-Index). V1/V2/V2.5/recovered/landing were archived **2026-08-31**.
- Do not invent metrics. Quote a repository's own description or README. If two public texts disagree (they do, on SLIC's city counts), report the disagreement.
- Do not scrape [flood.nonarkara.org](https://flood.nonarkara.org) for source. The licensed teacher is [FloodDash-Blueprint](https://github.com/Nonarkara/FloodDash-Blueprint).

---

## 1. Reconstruct from blueprints, not from the running building

The studio's clearest teaching object is a split:

| Layer | Where it lives | What you are allowed to take |
|---|---|---|
| **Invitation** | [FloodDash-Blueprint](https://github.com/Nonarkara/FloodDash-Blueprint) | Architecture, free data sources, the science, design language, a phased roadmap. Bilingual TH/EN. **No source code** — that is the point of the repo. |
| **Implementation** | private `FloodDash` | Purpose: production Thailand flood-monitoring system. Live: [flood.nonarkara.org](https://flood.nonarkara.org) |
| **Public cousin** | [nst-control-tower](https://github.com/Nonarkara/nst-control-tower) | A municipal tower that *does* publish source, flood-first, so a town can fork a city |

Quoted from the blueprint's own README:

> The blueprint, not the source code. / พิมพ์เขียว ไม่ใช่ซอร์สโค้ด.
>
> I built FloodDash after the Hat Yai floods of late 2025, because every piece of flood data Thailand needs … is already free, open, and machine-readable. The missing piece was never the data.
>
> I'm deliberately not handing out the source code for the version running today. Not out of possessiveness — out of curiosity. I want to know how many teams can build something this good, or better, on their own.

**Reconstruction drill:** read the blueprint end to end. List the data sources it names. Wire *your* geography. Compare your honesty labels (measured vs modelled) with [nst-control-tower](https://github.com/Nonarkara/nst-control-tower)'s public "data honesty" stance. Do not reverse-engineer the private app.

The same split appears elsewhere:

- Public [second-brain-os](https://github.com/Nonarkara/second-brain-os) vs private `second-brain-vault`
- Public [ikigai-finance](https://github.com/Nonarkara/ikigai-finance) vs private `ikigai-dashboard`
- Public [BKKx](https://github.com/Nonarkara/BKKx) / [BKKxCulture](https://github.com/Nonarkara/BKKxCulture) vs private `bkk-3d-atlas` at [atlas.nonarkara.org](https://atlas.nonarkara.org)

When both exist, **study the public one**. Use the private name only to understand that a production twin is running.

---

## 2. The one-Mac thesis

This studio does not argue for a data center. It argues that a serious civic picture can hang off **one machine, one person, one domain**.

Quoted from [dr-non-vibecoding-skills](https://github.com/Nonarkara/dr-non-vibecoding-skills):

> Six months. 1,691 commits. 110 always-on services running off one MacBook. 24 live public hostnames — all hanging off one domain, because subdomains are free and DNS doesn't care how ambitious you are.
> Three public-safety dashboards that real Thai citizens open during floods and dust season.
> One person. No team. No staging environment. No design department.

Quoted from [dr-non-agentic-ai-council](https://github.com/Nonarkara/dr-non-agentic-ai-council):

> A 9-bot AI council that thinks like a Manus-class team — runs on a Mac, costs ~$0-25/month. Divide and conquer, no supercomputer.

Quoted from FloodDash-Blueprint:

> a real, 24/7 flood-monitoring system for Thailand, running on one Mac right now

Quoted from [offline-ai-coding](https://github.com/Nonarkara/offline-ai-coding):

> Stop paying for tokens. Code with AI offline. One command setup.

**Reconstruction drill:** before you buy cloud, run [offline-ai-coding](https://github.com/Nonarkara/offline-ai-coding) and read the council repo. The constraint is the aesthetic: *if it needs a supercomputer to tell the truth about a river, the architecture is wrong.*

---

## 3. Fork a city

A control tower in this studio is not a unique snowflake. It is a **geography plug-in**: the same instincts (map as the page, flood-first where flood is the risk, open feeds, labelled models) pointed at a new municipality or campus.

**Public to fork**

- [nst-control-tower](https://github.com/Nonarkara/nst-control-tower) — Nakhon Si Thammarat, flood-first, MIT, bilingual README
- [city-hub](https://github.com/Nonarkara/city-hub) — Bangkok OS, "built independent of any single platform"
- [DrNon-Global-Satellite-Toolkit](https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit) — "Clone → pick your geography → deploy"
- [kuching-ioc](https://github.com/Nonarkara/kuching-ioc), [phuket-smart-bus](https://github.com/Nonarkara/phuket-smart-bus) — other public city-shaped objects

**Private (name + purpose only)** — Chulalongkorn, Yala, KMITL, Praram 9, Lopburi, Sikhio, Chonburi towers; `hcmc-dashboard`. These prove the pattern scaled. They are not the kit.

Quoted from the satellite toolkit listing:

> Open-source framework for building satellite-powered dashboards at any scale. 30 pluggable data modules (NASA, ESA, ACLED, GDELT, OpenSky, AQI, transit), 20+ satellite APIs from 80+ space agencies… Clone → pick your geography → deploy. Used in production smart city systems.

Quoted from NST's README:

> This dashboard exists to answer one question fast, during the hours that matter: "What is happening right now, and where do I send help?"

**Reconstruction drill:** clone the toolkit or NST. Change the bounding box. Replace feeds that do not apply. Keep the honesty labels. Publish *your* tower. That is the invitation.

---

## 4. No black-box rankings

SLIC exists because most city rankings will not show their work.

Quoted from the live [SLIC-Index](https://github.com/Nonarkara/SLIC-Index) listing:

> SLIC Index V3 — The city ranking that disagrees. 157 cities, 5 pillars, 35 signals, every score traceable. Not a ranking — a reality check. … Open source, free, no paywall, no black box.

Quoted from the V3 README:

> "Every city ranking is a lie. Here's ours."
>
> SLIC is the first city ranking that admits what it measures and why. … SLIC measures what's left after rent.

Quoted from archived [SLIC-Index-V2](https://github.com/Nonarkara/SLIC-Index-V2):

> Every city ranking is a lie. Here's ours.

Quoted from [slic-index-v1-recovered](https://github.com/Nonarkara/slic-index-v1-recovered):

> one declared formula, zero black boxes

[smart-city-thailand-index](https://github.com/Nonarkara/smart-city-thailand-index) applies the same allergy at national scale: "measuring reality, not paper plans. Built on SLIC methodology."

**Reconstruction drill:** fork V3, not an archive. Keep every score traceable. If you change a weight, say so on the page. If data is missing, a watchlist is more honest than a quiet drop — V3's README treats that as a feature.

When V3's listing (157 cities / 35 signals) and V3's README (163 cities, 158 ranked / 22 scored signals + 3 diagnostics) disagree, **do not average them**. Cite both. The ranking that disagrees should also be allowed to disagree with its own earlier caption.

---

## 5. Bilingual is not a locale switch; it is the audience

Thai and English sit in headings of this history because they sit in the work.

- FloodDash-Blueprint is explicitly **bilingual TH/EN** — the listing says so; the README leads with พิมพ์เขียว.
- NST ships `README.th.md` beside English.
- SLIC V3's README: "Multilingual — English, Thai, Chinese. Every piece of copy."
- [techhuntthailand](https://github.com/Nonarkara/techhuntthailand): trilingual showcase directory.
- [mean](https://github.com/Nonarkara/mean): 100 words across three languages.
- Axiom's public README: EN/TH/ZH/KO/JA/VI locale switch on the landing site.

**Reconstruction drill:** if the city you are instrumenting lives in Thai (or Malay, Vietnamese, Khmer), the operator UI cannot be English-only and still claim civic honesty. Translate the *argument*, not just the chrome.

---

## 6. The live-coding bible is the muscle memory

[live-coding-bible](https://github.com/Nonarkara/live-coding-bible) is small on disk and large as doctrine. Quoted:

> Dr Non's signature move: show different data sources on the same axis to reveal correlations that nobody thought to look for. He doesn't optimize milliseconds. He optimizes for:
> 1. Surprise — the moment a user sees two things together that they never expected to correlate
> 2. Reward — the feeling of capability that comes from acting on good information
> 3. Trust — the system earns the user's attention by being honest about what it doesn't know

Public tactics named in that README (study there, do not re-implement from rumour): multi-source correlation; a 5-minute cron that feels live; fleet health; satellite-first design (the map is the page); plan/room architecture; poison-proof deploys; three-job services.

[dr-non-vibecoding-skills](https://github.com/Nonarkara/dr-non-vibecoding-skills) packages the same production scars as **31 skills + 10 playbooks**, plain markdown, no runtime, loadable in Claude Code, Cursor, Codex, Gemini CLI, Aider, OpenCode.

**Reconstruction drill:** read the bible before generating a dashboard. If you are about to add a third chart library, stop. If two open APIs measure the same air, put them on one axis and let them argue.

---

## 7. Open data was already there

The origin reporter ([ORIGIN.md](ORIGIN.md)) and the flood blueprint agree on a single economic fact: **Thailand's civic data is not the scarce resource. Attention and wiring are.**

[ninja-innovation](https://github.com/Nonarkara/ninja-innovation), a public ebook:

> How a public servant replaces million-dollar platforms with curiosity and public data.

[city-hub](https://github.com/Nonarkara/city-hub):

> Built independent of any single platform.

**Reconstruction drill:** inventory feeds that are already free (the blueprint and the satellite toolkit list many). Build the correlation layer. Do not start with a procurement.

---

## 8. A suggested build order (stranger, one month of evenings)

Not a certificate. A path that stays inside public objects.

1. Read this file and the [README](README.md) once.
2. Open three live sites: [SLIC V3](https://nonarkara.github.io/SLIC-Index/), [FloodDash](https://flood.nonarkara.org) (look, don't scrape), [BKKx](https://bkk.nonarkara.org).
3. Read [FloodDash-Blueprint](https://github.com/Nonarkara/FloodDash-Blueprint) and [live-coding-bible](https://github.com/Nonarkara/live-coding-bible).
4. Clone [DrNon-Global-Satellite-Toolkit](https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit) *or* [nst-control-tower](https://github.com/Nonarkara/nst-control-tower). Point it at a geography you owe something to.
5. Load [dr-non-vibecoding-skills](https://github.com/Nonarkara/dr-non-vibecoding-skills) into whatever agent you actually use. Follow its deploy discipline; do not skip honesty labels.
6. If you need a ranking, fork [SLIC-Index](https://github.com/Nonarkara/SLIC-Index) V3 and declare your formula.
7. If you need a daily voice, wait until you have a corpus you have the right to use, then look at [Non-Cast](https://github.com/Nonarkara/Non-Cast) — empty at the 2026-08-31 audit; the listing is the invitation.

When you are done, you should have a system that is **yours**, running on **your** machine, arguing with **your** city's open data — without ever holding this studio's private keys.

---

<p align="center">The value isn't in the code you cannot see.<br/>The value is in knowing what problem to solve — and showing the work.</p>
