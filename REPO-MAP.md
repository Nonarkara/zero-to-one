# REPO-MAP

## แผนที่คลัง — public clusters, archives, private names

Public URLs are GitHub html_url values from the 31 August 2026 API snapshot. **Archived** means GitHub `archived: true` (pass of 2026-08-31 ICT). Private rows are **name + one-line purpose** from the studio map in this history's commission — not from private files.

Counts before *this* repository existed: **64 public, 58 private, 2 public forks**. After [zero-to-one](https://github.com/Nonarkara/zero-to-one): **65 public**. This map lists every public repo in the snapshot. It lists **notable** private repos only; it does not invent the rest of the 58.

Machine index: [artifacts/public-repos.csv](artifacts/public-repos.csv) · drawing: [artifacts/studio-map.svg](artifacts/studio-map.svg)

---

## 1. Origin · จุดกำเนิด

The account's first job. All three are **private**. Full essay: [ORIGIN.md](ORIGIN.md).

| Name | Visibility | Purpose (only) |
|---|---|---|
| `city-reporter-bot` | private | Original city-reporter bot — first purpose of the GitHub account (2024-10-18) |
| `city-reporter-v2` | private | Second-generation city reporter |
| `city-reporter-line-bot` | private | LINE-channel city reporter |

---

## 2. SLIC — the ranking that disagrees

Live line: **V3** only.

| Repository | Status | Created | Listing / role |
|---|---|---|---|
| [SLIC-Index](https://github.com/Nonarkara/SLIC-Index) | **live V3** | 2026-03-09 | "The city ranking that disagrees. 157 cities, 5 pillars, 35 signals, every score traceable." · [nonarkara.github.io/SLIC-Index](https://nonarkara.github.io/SLIC-Index/) |
| [slic-landing-page](https://github.com/Nonarkara/slic-landing-page) | **archived** | 2026-02-09 | V1 provocation, 103 cities |
| [SLIC-Index-V2.5](https://github.com/Nonarkara/SLIC-Index-V2.5) | **archived** | 2026-03-14 | Listing: V2, 174 cities / 53 countries, interactive spider |
| [SLIC-Index-V1](https://github.com/Nonarkara/SLIC-Index-V1) | **archived** | 2026-04-13 | "Original 103-city static ranking (archive)" |
| [SLIC-Index-V2](https://github.com/Nonarkara/SLIC-Index-V2) | **archived** | 2026-04-13 | "Every city ranking is a lie. Here's ours. (archive)" |
| [slic-index-v1-recovered](https://github.com/Nonarkara/slic-index-v1-recovered) | **archived** | 2026-07-22 | V1 recovered from SLIC-Index commit `6a614bb` |
| [smart-city-thailand-index](https://github.com/Nonarkara/smart-city-thailand-index) | live | 2026-04-01 | "measuring reality, not paper plans. Built on SLIC methodology." · [vercel app](https://smart-city-thailand-index.vercel.app) |
| [smart-city-thailand-monitor](https://github.com/Nonarkara/smart-city-thailand-monitor) | live | 2026-02-28 | Public monitor dashboard prototype |

---

## 3. Blueprints and reconstruction kit

Fork these to rebuild the *method*. Details: [PRINCIPLES.md](PRINCIPLES.md).

| Repository | Created | One line from the listing |
|---|---|---|
| [FloodDash-Blueprint](https://github.com/Nonarkara/FloodDash-Blueprint) | 2026-07-04 | Ideas behind FloodDash — architecture, free data, science, design, roadmap. No source code. TH/EN |
| [DrNon-Global-Satellite-Toolkit](https://github.com/Nonarkara/DrNon-Global-Satellite-Toolkit) | 2026-03-20 | Satellite-powered dashboards at any scale; clone, pick a geography, deploy |
| [live-coding-bible](https://github.com/Nonarkara/live-coding-bible) | 2026-04-09 | How data-heavy dashboards get built with AI |
| [dr-non-vibecoding-skills](https://github.com/Nonarkara/dr-non-vibecoding-skills) | 2026-08-13 | 31 skills + 10 playbooks from 1,691 commits and 110 always-on services |
| [Non-Claude-Skills](https://github.com/Nonarkara/Non-Claude-Skills) | 2026-03-26 | Claude Code skill stack: design system, APIs, satellite, news |
| [offline-ai-coding](https://github.com/Nonarkara/offline-ai-coding) | 2026-04-11 | One-command offline AI coding |
| [dr-non-agentic-ai-council](https://github.com/Nonarkara/dr-non-agentic-ai-council) | 2026-05-09 | 9-bot council on a Mac, ~$0–25/month |
| [dr-non-openclaw-setup](https://github.com/Nonarkara/dr-non-openclaw-setup) | 2026-08-09 | Agent-executable OpenClaw setup; docs only, no private data |
| [second-brain-os](https://github.com/Nonarkara/second-brain-os) | 2026-05-02 | Public operating-system pattern for an Obsidian + agent council |

---

## 4. Flood, air, and the private implementations they explain

| Name | Visibility | Purpose / listing |
|---|---|---|
| [FloodDash-Blueprint](https://github.com/Nonarkara/FloodDash-Blueprint) | public | Public invitation to rebuild a Thailand flood-monitoring system |
| `FloodDash` | **private** | Production flood-monitoring implementation; live [flood.nonarkara.org](https://flood.nonarkara.org) |
| [airdash](https://github.com/Nonarkara/airdash) | public | 24/7 air quality & PM2.5 watch for Thailand |
| `airdnd-platform` | **private** | Private product platform (AirDnD); internals not in public metadata |
| [nst-control-tower](https://github.com/Nonarkara/nst-control-tower) | public | Flood-first municipal control tower for Nakhon Si Thammarat |

---

## 5. Control towers · หอควบคุม (fork-a-city)

Public proof that a city tower can be published. Private siblings are named so a reader knows the family is larger than one MIT-licensed demo — not so they can open them.

| Name | Visibility | Purpose |
|---|---|---|
| [nst-control-tower](https://github.com/Nonarkara/nst-control-tower) | public | NST municipal tower, flood-first (React + deck.gl + Hono) |
| [city-hub](https://github.com/Nonarkara/city-hub) | public | Bangkok smart-city operating system |
| [kuching-ioc](https://github.com/Nonarkara/kuching-ioc) | public | Greater Kuching Intelligent Operation Center dashboard |
| [phuket-dashboard](https://github.com/Nonarkara/phuket-dashboard) | public | Phuket dashboard (listing has no description) |
| [phuket-smart-bus](https://github.com/Nonarkara/phuket-smart-bus) | public | Phuket Smart Bus rider prototype |
| `hcmc-dashboard` | **private** | Ho Chi Minh City dashboard |
| `chula` control tower | **private** | Chulalongkorn University / campus tower |
| `yala` control tower | **private** | Yala municipal tower |
| `kmitl` control tower | **private** | KMITL campus tower |
| `praram9` control tower | **private** | Praram 9 tower |
| `lopburi` control tower | **private** | Lopburi municipal tower |
| `sikhio` control tower | **private** | Sikhio municipal tower |
| `chonburi` control tower | **private** | Chonburi municipal tower |

The pattern: pick a geography, wire open feeds onto one map, tell the truth about modelled vs measured. Public source for that pattern is NST + City Hub + the satellite toolkit — not the private towers.

---

## 6. BKKx / atlas · กรุงเทพฯ ทีละบล็อก

| Name | Visibility | Purpose / listing |
|---|---|---|
| [BKKx](https://github.com/Nonarkara/BKKx) | public | "Bangkok, block by block — an open playable Minecraft city atlas" · [bkk.nonarkara.org](https://bkk.nonarkara.org) |
| [BKKxCulture](https://github.com/Nonarkara/BKKxCulture) | public | Heritage half of the pair (Fine Arts register, quarters, walks, 3D atlas view) |
| `bkk-3d-atlas` | **private** | Operational Bangkok digital twin; live [atlas.nonarkara.org](https://atlas.nonarkara.org) (named from the public BKKxCulture description) |

---

## 7. ASEAN, Thailand civic, geopolitics

| Repository | Created | Listing / live |
|---|---|---|
| [ascn-smart-cities-network](https://github.com/Nonarkara/ascn-smart-cities-network) | 2026-03-05 | ASCN V2 Progress Observatory · [ascn.nonarkara.org](https://ascn.nonarkara.org) |
| [ascnofficial](https://github.com/Nonarkara/ascnofficial) | 2026-03-05 | Public; no listing description |
| [asean-csco-app](https://github.com/Nonarkara/asean-csco-app) | 2026-02-10 | Public; no listing description |
| [solomon-islands-workshop](https://github.com/Nonarkara/solomon-islands-workshop) | 2026-03-04 | UN DESA × Solomon Islands digitalization workshop report |
| [techhuntthailand](https://github.com/Nonarkara/techhuntthailand) | 2026-03-05 | Smart City Thailand Tech Hunt, trilingual |
| [globalmonitor](https://github.com/Nonarkara/globalmonitor) | 2026-02-27 | Digital Economy Dashboard by depa · [github.io](https://nonarkara.github.io/globalmonitor/) |
| [globalmonitor-v3](https://github.com/Nonarkara/globalmonitor-v3) | 2026-06-19 | Geopolitical intelligence dashboard · [globalmonitor.pages.dev](https://globalmonitor.pages.dev) |
| [geopolitics-dashboard](https://github.com/Nonarkara/geopolitics-dashboard) | 2026-03-11 | Public; no listing description |
| [mem-by-non](https://github.com/Nonarkara/mem-by-non) | 2026-04-03 | Middle Eastern Monitor · [mem-by-non.vercel.app](https://mem-by-non.vercel.app) |
| [middleeast-monitor](https://github.com/Nonarkara/middleeast-monitor) | 2026-04-07 | Middle East War Monitor with PMUA, depa, Axiom |
| [non69](https://github.com/Nonarkara/non69) | 2026-03-26 | Thailand Watch Intelligence Dashboard |

---

## 8. Axiom, Each, finance, design

| Name | Visibility | Purpose / listing |
|---|---|---|
| [Axiom](https://github.com/Nonarkara/Axiom) | public | Innovation-as-a-service consultancy landing · [axiom.nonarkara.org](https://axiom.nonarkara.org) |
| [Axiom-Design-Core](https://github.com/Nonarkara/Axiom-Design-Core) | public | Living design system for Axiom decision systems |
| [Rams-NYCTA-Design-Core](https://github.com/Nonarkara/Rams-NYCTA-Design-Core) | public | Rams × NYCTA three-layer interface standard |
| [each](https://github.com/Nonarkara/each) | public | ERP · ACT · CRM · HR spine · [each.nonarkara.org](https://each.nonarkara.org) |
| [ikigai-finance](https://github.com/Nonarkara/ikigai-finance) | public | Open-source single-company financial cockpit |
| [ikigai-finance-engine](https://github.com/Nonarkara/ikigai-finance-engine) | public | SME finance intelligence research (development stage) |
| `ikigai-dashboard` | **private** | Private Ikigai dashboard implementation |
| `axiom-ops` | **private** | Operations for the Axiom practice |
| [RAAT](https://github.com/Nonarkara/RAAT) | public | Royal Automobile Association of Thailand |
| [scl-landing-page](https://github.com/Nonarkara/scl-landing-page) | public | Public; no listing description |
| [sciti](https://github.com/Nonarkara/sciti) | public | Public; no listing description |
| [dr-non-operating-systems](https://github.com/Nonarkara/dr-non-operating-systems) | public | Public; no listing description |
| [horizon](https://github.com/Nonarkara/horizon) | public | Public; no listing description |
| [luma-house](https://github.com/Nonarkara/luma-house) | public | Gesture-first home design prototype |
| [games](https://github.com/Nonarkara/games) | public | Public; no listing description |

---

## 9. Press, ebooks, dictionary, biography

There is **no public repository named `ebooks`** in this snapshot. The public flagship is the cluster:

| Repository | Created | Listing |
|---|---|---|
| [ninja-innovation](https://github.com/Nonarkara/ninja-innovation) | 2026-05-08 | Interactive ebook: public servant, public data, no million-dollar platform |
| [slowdown](https://github.com/Nonarkara/slowdown) | 2026-05-08 | Interactive art ebook — ten movements, public-domain artworks |
| [100-days-of-solitude](https://github.com/Nonarkara/100-days-of-solitude) | 2026-05-08 | Interactive ebook, butterfly page-flip, NON·ISM PRESS |
| [mean](https://github.com/Nonarkara/mean) | 2026-05-08 | 100 words across three languages |
| [100daysofnon](https://github.com/Nonarkara/100daysofnon) | 2026-05-24 | 100-day biographical installation, one publicly fact-checked question per day |

---

## 10. Voice, memory, RAG, other private notables

| Name | Visibility | Purpose |
|---|---|---|
| [Non-Cast](https://github.com/Nonarkara/Non-Cast) | public | Created 2026-08-31; **empty at audit**. Listing: "Fork this, add your corpus, get a daily podcast. Agent-agnostic." |
| `rag-nonarkara` | **private** | Private retrieval-augmented generation stack for the studio |
| `Ekkasarn-AI` | **private** | Private Ekkasarn AI — documents / records assistant |
| `second-brain-vault` | **private** | Working vault; public pattern is `second-brain-os` |
| `locating-shanghai` | **private** | Shanghai urban-location research / project |
| [council-watch](https://github.com/Nonarkara/council-watch) | public | Council health backstop |
| [nonarkara.org](https://github.com/Nonarkara/nonarkara.org) | public | Personal site source · [nonarkara.org](https://nonarkara.org) |
| [zero-to-one](https://github.com/Nonarkara/zero-to-one) | public | This reconstructable history |

---

## 11. Early personal landings — archived 2026-08-31

| Repository | Created | Listing |
|---|---|---|
| [non-landing-page](https://github.com/Nonarkara/non-landing-page) | 2026-02-24 | "city systems designer, anthropologist, novelist" |
| [non-landing-page-2](https://github.com/Nonarkara/non-landing-page-2) | 2026-02-24 | editorial minimalist landing |
| [non-landing-page-3](https://github.com/Nonarkara/non-landing-page-3) | 2026-02-24 | "Non Landing Page 3" |
| [non-landing-page-4](https://github.com/Nonarkara/non-landing-page-4) | 2026-02-25 | "City systems designer. Anthropologist. Novelist." |
| [non-landing-page-5](https://github.com/Nonarkara/non-landing-page-5) | 2026-02-26 | no listing description |

Live personal site is [nonarkara.org](https://nonarkara.org), not these archives.

---

## 12. Forks (the only two)

| Repository | Created | Upstream role (from listing) |
|---|---|---|
| [freellmapi](https://github.com/Nonarkara/freellmapi) | 2026-07-04 | OpenAI-compatible proxy over free LLM tiers; personal experimentation |
| [supabase](https://github.com/Nonarkara/supabase) | 2026-07-04 | Postgres development platform |

---

## How to use the map

- **Want to run something tonight?** Flagships with homepages in the [README](README.md#live-public-work--ของที่เปิดให้เข้าไปใช้).
- **Want to rebuild a city tower?** `nst-control-tower` + `DrNon-Global-Satellite-Toolkit` + `FloodDash-Blueprint`. Do not request private tower source.
- **Want the ranking?** `SLIC-Index` (V3). Treat V1/V2/V2.5/recovered/landing as **archives**.
- **Want Bangkok?** Public: `BKKx`, `BKKxCulture`, `city-hub`. Operational 3D twin: private `bkk-3d-atlas`, visible at [atlas.nonarkara.org](https://atlas.nonarkara.org).
- **Want the daily-brief instinct?** You cannot clone `city-reporter-bot`. You can read [ORIGIN.md](ORIGIN.md) and then look at City Hub, AirDash, and FloodDash-Blueprint — the public descendants of "make the city reportable."
