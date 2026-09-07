# Studio grammar

Municipal dashboards share one stack. SLIC is the public ranking that **disagrees** with how cities are usually scored. FloodDash-Blueprint is the gift; FloodDash is the running system.

```mermaid
flowchart TB
  subgraph grammar ["Shared municipal grammar"]
    S["React + deck.gl + Hono + Cloudflare"]
  end

  subgraph public_towers ["Public — fork these"]
    NST["nst-control-tower<br/>Nakhon Si Thammarat · flood-first"]
    CH["city-hub<br/>Bangkok OS"]
    PH["phuket-dashboard"]
    GEO["geopolitics-dashboard"]
    KU["kuching-ioc"]
    AIR["airdash"]
  end

  subgraph private_towers ["Private — purpose only"]
    CT["chula · yala · kmitl · praram9<br/>lopburi · sikhio · chonburi"]
    FD["FloodDash<br/>24/7 Thailand flood system · one Mac"]
    HCMC["hcmc-dashboard"]
  end

  subgraph disagree ["The ranking that disagrees"]
    SLIC["SLIC-Index V3 · live"]
    TH["smart-city-thailand-index"]
  end

  subgraph gift ["Blueprint vs implementation"]
    BP["FloodDash-Blueprint · public · no source of the live system"]
    LIVE["flood.nonarkara.org · live · implementation private"]
  end

  grammar --> public_towers
  grammar --> private_towers
  SLIC -.->|"not the same object as a control tower"| grammar
  BP -->|"ideas, data sources, science, roadmap"| LIVE
  FD --> LIVE
```
