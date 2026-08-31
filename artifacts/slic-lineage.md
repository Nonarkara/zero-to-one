# SLIC lineage

GitHub `created_at` is when the **repository object** appeared, not always when that version first went public. V3 lives in [`SLIC-Index`](https://github.com/Nonarkara/SLIC-Index), created 2026-03-09 — earlier than the later-created V1/V2 archive repos. The landing page (2026-02-09) is the first public SLIC object on this account.

```mermaid
flowchart TB
  subgraph origin ["First public SLIC object"]
    LP["slic-landing-page<br/>created 2026-02-09<br/>archived 2026-08-31"]
  end

  subgraph live ["Live"]
    V3["SLIC-Index · V3<br/>created 2026-03-09<br/>https://nonarkara.github.io/SLIC-Index/"]
  end

  subgraph archives ["Archived 2026-08-31 evening ICT"]
    V25["SLIC-Index-V2.5<br/>created 2026-03-14"]
    V1["SLIC-Index-V1<br/>created 2026-04-13"]
    V2["SLIC-Index-V2<br/>created 2026-04-13"]
    REC["slic-index-v1-recovered<br/>created 2026-07-22<br/>recovered from SLIC-Index commit 6a614bb"]
  end

  LP -->|"provocation · 103 cities"| V3
  V3 -->|"version snapshots / recoveries"| V25
  V3 --> V1
  V3 --> V2
  V3 --> REC
  V25 -.->|"archive · see V3"| V3
  V1 -.->|"archive · see V3"| V3
  V2 -.->|"archive · see V3"| V3
  REC -.->|"archive · see V3"| V3
  LP -.->|"archive · see V3"| V3
```

Public GitHub description of V3 at snapshot (quote, not a re-count):

> SLIC Index V3 — The city ranking that disagrees. 157 cities, 5 pillars, 35 signals, every score traceable. Not a ranking — a reality check. Launched at SCSE 2026 Taipei to 3,000 professionals. Open source, free, no paywall, no black box.
