# Repo map · แผนที่คลัง

Clusters of the [`Nonarkara`](https://github.com/Nonarkara) studio. Public URLs are GitHub HTML links. **Archived** is GitHub's flag after the 2026-08-31 evening ICT sweep. **Private** rows are name + one-line purpose only — no internals, no invented slugs beyond what the commissioning map (or a *public* description) already named.

Snapshot: public API, 2026-08-31. CSV: [`artifacts/public-repos.csv`](artifacts/public-repos.csv). Picture: [`artifacts/studio-clusters.svg`](artifacts/studio-clusters.svg).

---

## How to use this map

- **Fork / read / rebuild** anything public that is not archived, unless you are doing historiography.
- **Historiography** may read archived public repos. Do not treat them as current.
- **Private** means: you will get 404 without access. Purpose is enough.
- **Undated private family:** control towers listed as chula, yala, kmitl, praram9, lopburi, sikhio, chonburi — those are map names, not confirmed public slugs.
- Repos with an empty GitHub `description` are labelled *(no description at snapshot)*. I do not invent blurbs.

---

## 1 · Origin · จุดกำเนิด

Civic issue-reporting. First purpose of the account. All three **private**.

| Name | Visibility | Purpose |
|---|---|---|
| `city-reporter-bot` | private | **THE ORIGIN.** City-reporter bot; why the account was created 2024-10-18. |
| `city-reporter-v2` | private | Second-generation reporter. |
| `city-reporter-line-bot` | private | LINE-channel reporter. |

Narrative: [ORIGIN.md](ORIGIN.md).

---

## 2 · SLIC · the ranking that disagrees

| Repo | Created | Status | URL | GitHub description (snapshot) |
|---|---|---|---|---|
| [`slic-landing-page`](https://github.com/Nonarkara/slic-landing-page) | 2026-02-09 | **archived** | https://github.com/Nonarkara/slic-landing-page | SLIC Index V1 — original LinkedIn provocation, 103 cities. Homepage field: slic-index.onrender.com |
| [`SLIC-Index`](https://github.com/Nonarkara/SLIC-Index) | 2026-03-09 | **live V3** | https://github.com/Nonarkara/SLIC-Index | V3 — the city ranking that disagrees. Homepage: https://nonarkara.github.io/SLIC-Index/ |
| [`SLIC-Index-V2.5`](https://github.com/Nonarkara/SLIC-Index-V2.5) | 2026-03-14 | **archived** | https://github.com/Nonarkara/SLIC-Index-V2.5 | Described as V2; SCSE 2026 Taipei; 174 cities. Homepage: GitHub Pages V2.5 |
| [`SLIC-Index-V1`](https://github.com/Nonarkara/SLIC-Index-V1) | 2026-04-13 | **archived** | https://github.com/Nonarkara/SLIC-Index-V1 | Original 103-city static ranking (archive) |
| [`SLIC-Index-V2`](https://github.com/Nonarkara/SLIC-Index-V2) | 2026-04-13 | **archived** | https://github.com/Nonarkara/SLIC-Index-V2 | “Every city ranking is a lie. Here's ours.” (archive) |
| [`slic-index-v1-recovered`](https://github.com/Nonarkara/slic-index-v1-recovered) | 2026-07-22 | **archived** | https://github.com/Nonarkara/slic-index-v1-recovered | Recovered from SLIC-Index commit `6a614bb` |
| [`smart-city-thailand-index`](https://github.com/Nonarkara/smart-city-thailand-index) | 2026-04-01 | public | https://github.com/Nonarkara/smart-city-thailand-index | Thailand index on SLIC methodology. Live: https://smart-city-thailand-index.vercel.app |
| [`smart-city-thailand-monitor`](https://github.com/Nonarkara/smart-city-thailand-monitor) | 2026-02-28 | public | https://github.com/Nonarkara/smart-city-thailand-monitor | Public monitor dashboard prototype |

**Fork V3, not the archives.** Lineage diagram: [`artifacts/slic-lineage.md`](artifacts/slic-lineage.md).

---

## 3 · Control towers · fork a city

Shared grammar (stated on the public NST repo): **React + deck.gl + Hono + Cloudflare**.

### Public

| Repo | Created | URL | Notes |
|---|---|---|---|
| [`nst-control-tower`](https://github.com/Nonarkara/nst-control-tower) | 2026-06-22 | https://github.com/Nonarkara/nst-control-tower | Nakhon Si Thammarat, flood-first. **The public tower to fork.** |
| [`city-hub`](https://github.com/Nonarkara/city-hub) | 2026-05-26 | https://github.com/Nonarkara/city-hub | Bangkok smart-city OS sketch |
| [`phuket-dashboard`](https://github.com/Nonarkara/phuket-dashboard) | 2026-03-12 | https://github.com/Nonarkara/phuket-dashboard | Phuket map-first monitor *(no GitHub description)* |
| [`geopolitics-dashboard`](https://github.com/Nonarkara/geopolitics-dashboard) | 2026-03-11 | https://github.com/Nonarkara/geopolitics-dashboard | Public README: clone-source for Phuket *(no GitHub description)* |
| [`phuket-smart-bus`](https://github.com/Nonarkara/phuket-smart-bus) | 2026-03-08 | https://github.com/Nonarkara/phuket-smart-bus | Rider prototype |
| [`kuching-ioc`](https://github.com/Nonarkara/kuching-ioc) | 2026-04-11 | https://github.com/Nonarkara/kuching-ioc | Greater Kuching Intelligent Operation Center |
| [`airdash`](https://github.com/Nonarkara/airdash) | 2026-07-16 | https://github.com/Nonarkara/airdash | 24/7 air quality & PM2.5 watch for Thailand |
| [`non69`](https://github.com/Nonarkara/non69) | 2026-03-26 | https://github.com/Nonarkara/non69 | Thailand Watch Intelligence Dashboard |

### Private (purpose only)

| Name | Purpose |
|---|---|
| chula, yala, kmitl, praram9, lopburi, sikhio, chonburi | Municipal control towers sharing the public grammar. Exact private slugs not confirmed from the public API. |
| `hcmc-dashboard` | Ho Chi Minh City dashboard. |

---

## 4 · FloodDash · gift vs running system

| Name | Visibility | Created | URL / live | Purpose |
|---|---|---|---|---|
| [`FloodDash-Blueprint`](https://github.com/Nonarkara/FloodDash-Blueprint) | **public** | 2026-07-04 | https://github.com/Nonarkara/FloodDash-Blueprint | Architecture, free data sources, science, design language, build-your-own roadmap. **No source of the live system.** Bilingual TH/EN. |
| `FloodDash` | **private** | — | live site [flood.nonarkara.org](https://flood.nonarkara.org) | 24/7 Thailand flood system, one Mac. |

Do not ask this history for the private implementation. The blueprint is the gift.

---

## 5 · Bangkok atlas / BKKx

| Name | Visibility | Created | URL | Notes |
|---|---|---|---|---|
| [`BKKx`](https://github.com/Nonarkara/BKKx) | public | 2026-08-03 | https://github.com/Nonarkara/BKKx | Bangkok, block by block — open playable Minecraft city atlas. Live: [bkk.nonarkara.org](https://bkk.nonarkara.org) |
| [`BKKxCulture`](https://github.com/Nonarkara/BKKxCulture) | public | 2026-08-11 | https://github.com/Nonarkara/BKKxCulture | Heritage half: Fine Arts Department register, quarters, walks, 3D atlas view |
| `bkk-3d-atlas` | **private** | — | named on BKKxCulture as atlas.nonarkara.org | Operational digital twin — purpose only |

---

## 6 · Satellite, ASEAN, global monitors

| Repo | Created | URL | Homepage / live |
|---|---|---|---|
| [`DrNon-Global-Satellite-Toolkit`](https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit) | 2026-03-20 | https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit | *(none in API)* — public framework |
| [`globalmonitor`](https://github.com/Nonarkara/globalmonitor) | 2026-02-27 | https://github.com/Nonarkara/globalmonitor | https://nonarkara.github.io/globalmonitor/ |
| [`globalmonitor-v3`](https://github.com/Nonarkara/globalmonitor-v3) | 2026-06-19 | https://github.com/Nonarkara/globalmonitor-v3 | https://globalmonitor.pages.dev |
| [`ascn-smart-cities-network`](https://github.com/Nonarkara/ascn-smart-cities-network) | 2026-03-05 | https://github.com/Nonarkara/ascn-smart-cities-network | https://ascn.nonarkara.org |
| [`ascnofficial`](https://github.com/Nonarkara/ascnofficial) | 2026-03-05 | https://github.com/Nonarkara/ascnofficial | *(no description)* |
| [`mem-by-non`](https://github.com/Nonarkara/mem-by-non) | 2026-04-03 | https://github.com/Nonarkara/mem-by-non | https://mem-by-non.vercel.app |
| [`middleeast-monitor`](https://github.com/Nonarkara/middleeast-monitor) | 2026-04-07 | https://github.com/Nonarkara/middleeast-monitor | — |
| [`techhuntthailand`](https://github.com/Nonarkara/techhuntthailand) | 2026-03-05 | https://github.com/Nonarkara/techhuntthailand | — |
| [`solomon-islands-workshop`](https://github.com/Nonarkara/solomon-islands-workshop) | 2026-03-04 | https://github.com/Nonarkara/solomon-islands-workshop | — |

---

## 7 · Method · public blueprints (reconstruct from these)

| Repo | Created | URL | Why it is here |
|---|---|---|---|
| [`FloodDash-Blueprint`](https://github.com/Nonarkara/FloodDash-Blueprint) | 2026-07-04 | https://github.com/Nonarkara/FloodDash-Blueprint | Gift: flood system without the private code |
| [`DrNon-Global-Satellite-Toolkit`](https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit) | 2026-03-20 | https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit | Gift: satellite dashboards at any scale |
| [`SLIC-Index`](https://github.com/Nonarkara/SLIC-Index) | 2026-03-09 | https://github.com/Nonarkara/SLIC-Index | Gift: ranking with traceable scores |
| [`live-coding-bible`](https://github.com/Nonarkara/live-coding-bible) | 2026-04-09 | https://github.com/Nonarkara/live-coding-bible | Gift: how the dashboards are built with AI |
| [`dr-non-vibecoding-skills`](https://github.com/Nonarkara/dr-non-vibecoding-skills) | 2026-08-13 | https://github.com/Nonarkara/dr-non-vibecoding-skills | Gift: skills + playbooks in plain markdown |
| [`Non-Claude-Skills`](https://github.com/Nonarkara/Non-Claude-Skills) | 2026-03-26 | https://github.com/Nonarkara/Non-Claude-Skills | Earlier Claude Code skill stack |
| [`offline-ai-coding`](https://github.com/Nonarkara/offline-ai-coding) | 2026-04-11 | https://github.com/Nonarkara/offline-ai-coding | Offline AI coding setup |
| [`dr-non-openclaw-setup`](https://github.com/Nonarkara/dr-non-openclaw-setup) | 2026-08-09 | https://github.com/Nonarkara/dr-non-openclaw-setup | Agent-executable OpenClaw setup; docs only |
| [`dr-non-agentic-ai-council`](https://github.com/Nonarkara/dr-non-agentic-ai-council) | 2026-05-09 | https://github.com/Nonarkara/dr-non-agentic-ai-council | 9-bot council on a Mac |
| this repo [`zero-to-one`](https://github.com/Nonarkara/zero-to-one) | 2026-08-31 | https://github.com/Nonarkara/zero-to-one | Reconstructable history |

[PRINCIPLES.md](PRINCIPLES.md) is the reconstruction order. [START-HERE.md](START-HERE.md) is the shorter teaching door.

---

## 8 · Axiom, Each, finance, studio OS

### Public

| Repo | Created | URL | Notes |
|---|---|---|---|
| [`Axiom`](https://github.com/Nonarkara/Axiom) | 2026-03-15 | https://github.com/Nonarkara/Axiom | Innovation as a Service landing page |
| [`Axiom-Design-Core`](https://github.com/Nonarkara/Axiom-Design-Core) | 2026-06-26 | https://github.com/Nonarkara/Axiom-Design-Core | Living design system |
| [`Rams-NYCTA-Design-Core`](https://github.com/Nonarkara/Rams-NYCTA-Design-Core) | 2026-06-26 | https://github.com/Nonarkara/Rams-NYCTA-Design-Core | Rams × NYCTA interface standard |
| [`each`](https://github.com/Nonarkara/each) | 2026-06-27 | https://github.com/Nonarkara/each | ERP · ACT · CRM · HR. Live: https://each.nonarkara.org |
| [`ikigai-finance`](https://github.com/Nonarkara/ikigai-finance) | 2026-07-28 | https://github.com/Nonarkara/ikigai-finance | **OSS cockpit** — the public finance slice |
| [`ikigai-finance-engine`](https://github.com/Nonarkara/ikigai-finance-engine) | 2026-06-26 | https://github.com/Nonarkara/ikigai-finance-engine | Research / development stage |
| [`second-brain-os`](https://github.com/Nonarkara/second-brain-os) | 2026-05-02 | https://github.com/Nonarkara/second-brain-os | Public personal OS sketch |
| [`council-watch`](https://github.com/Nonarkara/council-watch) | 2026-05-04 | https://github.com/Nonarkara/council-watch | Council health backstop |
| [`nonarkara.org`](https://github.com/Nonarkara/nonarkara.org) | 2026-05-08 | https://github.com/Nonarkara/nonarkara.org | Personal site. Live: https://nonarkara.org |
| [`dr-non-operating-systems`](https://github.com/Nonarkara/dr-non-operating-systems) | 2026-03-08 | https://github.com/Nonarkara/dr-non-operating-systems | *(no description)* |

### Private (purpose only)

| Name | Purpose |
|---|---|
| `ikigai-dashboard` | SME finance cockpit, PII-adjacent — private for that reason. |
| `axiom-ops` | Studio operations, including a podcast pipeline. |
| `second-brain-vault` | Private vault beside public `second-brain-os`. |
| `rag-nonarkara` | Named in the studio map (retrieval store). |
| `Ekkasarn-AI` | Named in the studio map; purpose not expanded beyond the name. |
| `airdnd-platform` | Bangkok spa / civic map. |

---

## 9 · Writing, press, voice, play

| Repo | Created | Status | URL | Notes |
|---|---|---|---|---|
| [`100-days-of-solitude`](https://github.com/Nonarkara/100-days-of-solitude) | 2026-05-08 | public | https://github.com/Nonarkara/100-days-of-solitude | Interactive ebook, NON·ISM PRESS |
| [`100daysofnon`](https://github.com/Nonarkara/100daysofnon) | 2026-05-24 | public | https://github.com/Nonarkara/100daysofnon | 100-day biographical installation |
| [`slowdown`](https://github.com/Nonarkara/slowdown) | 2026-05-08 | public | https://github.com/Nonarkara/slowdown | Interactive art ebook |
| [`ninja-innovation`](https://github.com/Nonarkara/ninja-innovation) | 2026-05-08 | public | https://github.com/Nonarkara/ninja-innovation | Public servant vs million-dollar platforms |
| [`mean`](https://github.com/Nonarkara/mean) | 2026-05-08 | public | https://github.com/Nonarkara/mean | 100 words, three languages |
| [`Non-Cast`](https://github.com/Nonarkara/Non-Cast) | 2026-08-31 | public | https://github.com/Nonarkara/Non-Cast | Fork this, add your corpus, get a daily podcast. Empty at the commissioning audit; see [TIMELINE.md](TIMELINE.md) |
| [`horizon`](https://github.com/Nonarkara/horizon) | 2026-06-01 | public | https://github.com/Nonarkara/horizon | *(no description)*; README: Neural Calibration |
| [`luma-house`](https://github.com/Nonarkara/luma-house) | 2026-07-15 | public | https://github.com/Nonarkara/luma-house | Gesture-first home design prototype |
| [`games`](https://github.com/Nonarkara/games) | 2026-08-05 | public | https://github.com/Nonarkara/games | *(no description)* |
| `locating-shanghai` | — | **private** | — | Routledge monograph workspace. Purpose only. |

---

## 10 · Identity landing-page experiments · archived 2026-08-31

| Repo | Created | URL |
|---|---|---|
| [`non-landing-page`](https://github.com/Nonarkara/non-landing-page) | 2026-02-24 | https://github.com/Nonarkara/non-landing-page |
| [`non-landing-page-2`](https://github.com/Nonarkara/non-landing-page-2) | 2026-02-24 | https://github.com/Nonarkara/non-landing-page-2 |
| [`non-landing-page-3`](https://github.com/Nonarkara/non-landing-page-3) | 2026-02-24 | https://github.com/Nonarkara/non-landing-page-3 |
| [`non-landing-page-4`](https://github.com/Nonarkara/non-landing-page-4) | 2026-02-25 | https://github.com/Nonarkara/non-landing-page-4 |
| [`non-landing-page-5`](https://github.com/Nonarkara/non-landing-page-5) | 2026-02-26 | https://github.com/Nonarkara/non-landing-page-5 |

Surviving public identity: [`nonarkara.org`](https://github.com/Nonarkara/nonarkara.org), [`Axiom`](https://github.com/Nonarkara/Axiom).

---

## 11 · Other public (uncategorized on purpose)

| Repo | Created | URL | Notes |
|---|---|---|---|
| [`asean-csco-app`](https://github.com/Nonarkara/asean-csco-app) | 2026-02-10 | https://github.com/Nonarkara/asean-csco-app | *(no description)* |
| [`scl-landing-page`](https://github.com/Nonarkara/scl-landing-page) | 2026-03-08 | https://github.com/Nonarkara/scl-landing-page | *(no description)*; README names scl.nonarkara.org |
| [`RAAT`](https://github.com/Nonarkara/RAAT) | 2026-03-08 | https://github.com/Nonarkara/RAAT | The Royal Automobile Association of Thailand |
| [`sciti`](https://github.com/Nonarkara/sciti) | 2026-05-07 | https://github.com/Nonarkara/sciti | *(no description)* |

---

## 12 · Forks (2)

| Repo | Created | URL | Notes |
|---|---|---|---|
| [`freellmapi`](https://github.com/Nonarkara/freellmapi) | 2026-07-04 | https://github.com/Nonarkara/freellmapi | Fork. Homepage: https://freellmapi.co |
| [`supabase`](https://github.com/Nonarkara/supabase) | 2026-07-04 | https://github.com/Nonarkara/supabase | Fork. Homepage: https://supabase.com |

Not studio originals. Listed so the public census is complete.

---

## What is not on this map

About **58** private repositories existed at the audit before `zero-to-one`. Only the names the commissioning map authorized appear above. The rest stay unnamed. That is how this history stays generous without becoming a leak.

Login: **Nonarkara** (same as nonarkara). Organizations: **none**.
