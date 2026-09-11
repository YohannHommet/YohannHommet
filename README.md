### Yohann Hommet

Software Engineer based in France. Working on backend systems, networking protocols, developer tooling, and web products.

I design systems around **black-box architecture**: deep modules with small interfaces, explicit failure handling, and strict boundary isolation.

---

#### Featured Projects

* **[walspool](https://github.com/YohannHommet/walspool)** — In-process Write-Ahead Log (WAL) and OpenTelemetry ingestion hub in pure Go. Buffers high-throughput telemetry to disk with zero heap allocations in the hot path. ([docs](https://yohannhommet.github.io/walspool/))
* **[wisp](https://github.com/YohannHommet/wisp)** — P2P encrypted file transfer protocol and CLI in Rust. Runs direct transfers over QUIC and ephemeral TLS 1.3, authenticated via SPAKE2 (RFC 9382) with BLAKE3 streaming verification and a stateless rendezvous relay.
* **[argus](https://github.com/YohannHommet/argus)** — Observability backend and UI for Claude Code telemetry. Ingests OTLP spans, tracks session costs, and renders subagent execution trees. *(Go, Vue 3, PostgreSQL)*
* **[Unfurl](https://unfurlit.vercel.app/)** — SSRF-safe link preview and metadata extraction API. Validates redirects per hop to block internal network access, caches in Redis, and meters usage via Stripe.
* **[LinkBounty](https://github.com/YohannHommet/linkbounty)** — High-concurrency website broken link checker in pure Go. Worker pool concurrency, SSRF protection against DNS rebinding, pure-Go SQLite storage, and HTMX.
* **[pg-lens-mcp](https://github.com/YohannHommet/pg-lens-mcp)** — Lightweight Model Context Protocol (MCP) server for PostgreSQL schema inspection and queries.

---

#### Tech & Environment

* **Languages & Core**: Go, Rust, TypeScript, PHP, SQL, Shell
* **Protocols & Data**: QUIC / TLS 1.3, SPAKE2, BLAKE3, OTLP, PostgreSQL, SQLite, Redis
* **Daily Setup**: Linux, Zed, Claude Code, Antigravity CLI, Codex

---

[Portfolio](https://yohann-hommet.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/yohann-hommet/) · [Twitter / X](https://twitter.com/Yohann_Dev) · [yohann.hommet@outlook.fr](mailto:yohann.hommet@outlook.fr)
