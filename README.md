# Digital Rain Technologies

**Building systems that reason.**

We build tools that help enterprises navigate AI adoption and legacy system modernization — with a focus on governance, safety, and auditability. 10 years building Master Data Management systems at Informatica, now applied to AI. Systems need to be robust before they can be clever.

Founded by [Augustin Chan](https://augustinchan.dev) — former Development Architect at Informatica with 12+ years leading enterprise architecture for Fortune 500 customers across APAC, MENA, and Europe. BS Cognitive Science (Computation), UC San Diego.

---

## Open Source

### [ARA-Eval](https://github.com/digital-rain-tech/ara-eval) — Agentic Readiness Assessment

Open evaluation framework for determining when enterprises can safely deploy autonomous AI agents. Instead of collapsing risk into a single score, ARA-Eval produces **risk fingerprints** — 7-dimension classifications that preserve reasoning and enable deterministic gating rules.

- **7 dimensions:** Decision Reversibility, Failure Blast Radius, Regulatory Exposure, Human Override Latency, Data Confidence, Accountability Chain, Graceful Degradation
- **Deterministic gating:** Policy rules are applied programmatically, never delegated to the LLM
- **Multi-stakeholder perspectives:** ConFIRM method surfaces alignment gaps across compliance, risk, and operations viewpoints
- **Hong Kong financial services focus:** Built against HKMA, SFC, and PCPD regulatory frameworks

Developed in collaboration with [IRAI Labs](https://irailabs.com).

### [Crawl](https://github.com/digital-rain-tech/crawl) — Pre-Migration Intelligence

Extracts and analyzes business logic from stored procedures, ETL jobs, and warehouse views — the undocumented rules encoded in vendor-specific SQL that block every migration project. Crawl is **Step 0**, before tools like dbt, Datafold, or SnowConvert.

- **Multi-source parsing:** Oracle Data Integrator (live DB + offline XML), Informatica PowerCenter, with PostgreSQL and Snowflake planned
- **Migration intelligence:** Contradiction detection, vendor-specific syntax flagging, dead code identification, complexity scoring
- **Enterprise safety model:** Read-only queries, catalog-only access, query allowlisting, credential redaction, full audit trail
- **Common IR:** All parsers produce a unified intermediate representation for source-agnostic analysis

---

## Other Projects

- **[8-Bit Oracle](https://8bitoracle.ai)** — Modular I-Ching divination platform. Winner of the OriginTrail track at Consensus HK 2025 ([CoinDesk coverage](https://www.coindesk.com))
- **[Six Lines](https://sixlines.online)** — Native iOS I-Ching app built on primary sources, including 3,600+ scanned Qing imperial manuscript pages
- **[Ridgeline](https://ridgeline.works)** — Surgical field provisioning software for Outward Bound Hong Kong
- **[Hong Kong AI Podcast](https://hongkongaipodcast.com)** — Covering AI builders in the Greater Bay Area

---

## Links

| | |
|---|---|
| **Company** | [digitalrain.dev](https://digitalrain.dev) |
| **Founder** | [augustinchan.dev](https://augustinchan.dev) |
| **Twitter/X** | [@aug_digitalrain](https://x.com/aug_digitalrain) |
| **LinkedIn** | [linkedin.com/in/auchan](https://www.linkedin.com/in/auchan) |
| **Contact** | contact@digitalrain.studio |

## License

ARA-Eval and Crawl are released under the [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) license.
