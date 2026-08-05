# Zubair Muwwakil

**Full-Stack Software Engineer — backend-leaning.** Brooklyn, NY.

I build data-driven products where the interesting problems sit behind the API: schema
design, query performance, idempotent reprocessing, and the observability that tells you
when any of it breaks.

Currently a contract Software Engineer at **G2i Inc.**, building Django backend services —
REST APIs, background jobs, and data processing — and owning the PostgreSQL / SQL Server
changes that ship through Dockerized CI gates.

- Portfolio and case studies — **[zubairmuwwakil.com](https://zubairmuwwakil.com)**
- LinkedIn — **[in/zubairmuwwakil](https://www.linkedin.com/in/zubairmuwwakil/)**
- Résumé — **[zubairmuwwakil.com/resume](https://zubairmuwwakil.com/resume/)**

## What I work with

| | |
|---|---|
| **Languages** | Java, Python, TypeScript / JavaScript, C#, SQL |
| **Backend** | Spring Boot, Django, REST APIs, OpenAPI / Swagger |
| **Frontend** | React, Next.js, React Native |
| **Data** | PostgreSQL, SQL Server (T-SQL), Prisma, Flyway, indexing and query tuning |
| **Reliability** | Micrometer / Prometheus, OpenTelemetry (OTLP), structured logging, tracing |
| **DevOps** | Docker, GitHub Actions, JUnit, Spring Boot Test |

## Things I've shipped

### [PickleOps — The Pickleball Social](https://apps.apple.com/us/app/the-pickleball-social/id6759585852)
`React Native` `TypeScript` `Prisma` `PostgreSQL` `iOS`

A live iOS app for running club pickleball — sessions, ladders, ratings, and payments in one
place. Shipped to the App Store and maintained through 21 releases in five months, with
offline-first sync and version conflict resolution, atomic match finalization, DUPR single
sign-on with opt-in write-back, and Bluetooth proximity discovery behind consent gates.
[Case study →](https://zubairmuwwakil.com/projects/pickleops/)

### [MarketLens — Market Data Pipeline & Analytics Service](https://marketdata.zubairmuwwakil.com)
`Java 21` `Spring Boot 4` `PostgreSQL` `Flyway`

Market data ingestion and analytics behind an API-key-authed REST surface with OpenAPI docs.
Idempotent ingestion with run tracking and retries handles ~50k–250k rows per run using
composite keys, upserts, and yearly partitioning for time-series queries at scale.
Productionized with Bucket4j rate limiting and quota tracking, Prometheus metrics,
correlation-ID structured logs, OTLP tracing, and data-quality checks for missing days,
duplicates, and outliers. [Case study →](https://zubairmuwwakil.com/projects/marketlens/)

### [Looply — Returns, Subscriptions & Receipt Automation](https://looply.zubairmuwwakil.com)
`Next.js` `React 19` `TypeScript` `Prisma` `PostgreSQL`

A finance assistant that tracks subscriptions, bills, receipts, and return/refund deadlines
from inbox data. Receipt ingestion runs over Gmail OAuth with PDF/HTML parsing — ~200 emails
per run, ~30–60 receipts extracted at ~88% parse success — feeding cron-triggered digest and
notification automations with Postgres job tracking and retry-safe reprocessing.
[Case study →](https://zubairmuwwakil.com/projects/looply/)

### [MindSky — Visual Thought Mapping](https://mindsky.zubairmuwwakil.com)
`React` `TypeScript` `React Flow` `Node.js` `PostgreSQL`

Infinite-canvas thought mapping with snapshot-based undo/redo and debounced autosave,
persisting each map as a whole graph in Postgres JSONB.
[Case study →](https://zubairmuwwakil.com/projects/mindsky/)

---

Alongside the above I built and deployed **[pbsocial.ca](https://pbsocial.ca)**, a multi-tenant
Next.js/TypeScript/PostgreSQL platform for session scheduling, registrations, attendance, and
reporting — automatic group and match generation, atomic match finalization, and Glicko-2
ratings with standings history. It scaled from ~50 to 1,000+ participants.

**BSc, Computer Science & Mathematics** — University of Toronto · USA & Canadian citizen

Open to backend and full-stack roles. Reach me at **zmuwwakil@gmail.com**.
