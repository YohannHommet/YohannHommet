<div align="center">

# Yohann Hommet
### **Software Engineer** · Systems, Network Protocols & Developer Tooling

[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-0ea5e9?style=for-the-badge&logo=firefox-browser&logoColor=white)](https://yohann-hommet.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-YohannHommet-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YohannHommet)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yohann_Hommet-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yohann-hommet/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yohann.hommet@outlook.fr)

<br />

> *Designing zero-allocation data engines, secure peer-to-peer protocols, and developer-facing SaaS products under strict **Black-Box Architecture** principles.*

<br />

<p align="center">
  <img src="https://img.shields.io/badge/Editor-Zed-08090a?style=flat-square&logo=zed&logoColor=white" alt="Zed Editor" />
  <img src="https://img.shields.io/badge/Harness-Claude_Code-D97706?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Agent-Antigravity_CLI-4F46E5?style=flat-square&logo=google&logoColor=white" alt="Antigravity CLI" />
  <img src="https://img.shields.io/badge/Agent-Codex-10B981?style=flat-square&logo=openai&logoColor=white" alt="Codex" />
  <img src="https://img.shields.io/badge/Doctrine-Black--Box-181717?style=flat-square&logo=cube&logoColor=white" alt="Black-Box Architecture" />
</p>

</div>

---

### About

Software Engineer based in France. I build backend services, network protocols, and developer tools in Go and Rust, alongside web apps and APIs.

* **Architecture**: Black-box design principles — deep modules with narrow public interfaces, explicit error handling, and zero leaky internals.
* **Daily setup**: Linux, Zed, Claude Code, Antigravity CLI, Codex.

---

### Core Systems & Networking

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/YohannHommet/walspool">walspool</a></h3>
      <p><em>In-process Write-Ahead Log (WAL) & OpenTelemetry hub in Go</em></p>
      <p>Buffers high-throughput telemetry to disk during upstream outages with zero heap allocations on the hot path. Prevents OOM crashes under sudden traffic spikes.</p>
      <p>
        <img src="https://img.shields.io/badge/Go_1.22+-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OTel" />
        <img src="https://img.shields.io/badge/Zero--Alloc-CCFF00?style=flat-square&logoColor=black&labelColor=16171C" alt="Zero-Alloc" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      </p>
      <ul>
        <li>Dual memory ring-buffer & disk segment engine</li>
        <li>Crash-resilient sub-millisecond recovery replay</li>
        <li><a href="https://yohannhommet.github.io/walspool/">Documentation & Benchmarks</a></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/YohannHommet/wisp">wisp</a></h3>
      <p><em>Encrypted P2P file transfer protocol in Rust</em></p>
      <p>Direct peer-to-peer file transfer engine over QUIC and ephemeral TLS 1.3. Mutual password authentication with SPAKE2 (RFC 9382) and streaming BLAKE3 verification.</p>
      <p>
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust" />
        <img src="https://img.shields.io/badge/QUIC-TLS_1.3-00599C?style=flat-square" alt="QUIC" />
        <img src="https://img.shields.io/badge/SPAKE2-RFC_9382-10B981?style=flat-square" alt="SPAKE2" />
        <img src="https://img.shields.io/badge/BLAKE3-Verified-2563EB?style=flat-square" alt="BLAKE3" />
      </p>
      <ul>
        <li>Direct 1-RTT encrypted QUIC transport</li>
        <li>Password-authenticated key exchange (SPAKE2)</li>
        <li>Stateless blind rendezvous relay built with Axum</li>
      </ul>
    </td>
  </tr>
</table>

---

### Agentic AI & Observability

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔍 <a href="https://github.com/YohannHommet/argus">argus</a></h3>
      <p><em>OTLP telemetry backend & session explorer for Claude Code</em></p>
      <p>Observability backend and UI ingesting OTLP spans from autonomous coding agent sessions. Tracks token consumption, latency, and subagent call trees in real time.</p>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Vue.js_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres" />
      </p>
      <ul>
        <li>Subagent call-graph and decision tracing</li>
        <li>Cost and latency breakdown per session</li>
        <li>PostgreSQL-backed time-series storage</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔌 <a href="https://github.com/YohannHommet/pg-lens-mcp">pg-lens-mcp</a></h3>
      <p><em>PostgreSQL Model Context Protocol (MCP) server</em></p>
      <p>Lightweight MCP server giving coding agents safe access to PostgreSQL databases for schema discovery, table structures, and targeted queries.</p>
      <p>
        <img src="https://img.shields.io/badge/Protocol-MCP-8A2BE2?style=flat-square" alt="MCP" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres" />
      </p>
      <ul>
        <li>Read-oriented schema catalog & table introspection</li>
        <li>Isolated query boundary with minimal attack surface</li>
        <li>Compatible with Claude Code, Zed, and standard MCP clients</li>
      </ul>
    </td>
  </tr>
</table>

---

### Developer Tools & Web Products

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔗 <a href="https://unfurlit.vercel.app/">Unfurl</a></h3>
      <p><em>SSRF-safe link preview & metadata extraction API</em></p>
      <p>Developer-facing API turning URLs into clean metadata JSON (title, description, social cards, icons). Hardened against SSRF by validating redirects per hop to block cloud metadata and internal subnets.</p>
      <p>
        <img src="https://img.shields.io/badge/Live_Product-unfurlit.vercel.app-0ea5e9?style=flat-square" alt="Unfurl" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Stripe-Billing-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe" />
        <img src="https://img.shields.io/badge/Redis-Cache-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      </p>
      <ul>
        <li>Hop-by-hop IP validation against DNS rebinding</li>
        <li>Redis response cache with <code>X-Cache</code> headers</li>
        <li>Metered API keys with Stripe self-serve billing</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🎯 <a href="https://github.com/YohannHommet/linkbounty">LinkBounty</a></h3>
      <p><em>Concurrent website broken link checker in pure Go</em></p>
      <p>Crawls websites and verifies internal and outbound links concurrently using a goroutine worker pool. Generates shareable audit reports.</p>
      <p>
        <img src="https://img.shields.io/badge/Go_1.25+-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/SQLite-WAL_Mode-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
        <img src="https://img.shields.io/badge/HTMX-SSR-3366CC?style=flat-square&logo=htmx&logoColor=white" alt="HTMX" />
        <img src="https://img.shields.io/badge/Zero--CGO-Pure--Go-10B981?style=flat-square" alt="Zero CGO" />
      </p>
      <ul>
        <li>Pooled workers with automated anti-bot HTTP fallbacks</li>
        <li>SSRF protection against private IP targets</li>
        <li>Single binary with pure-Go SQLite storage (WAL mode) and HTMX UI</li>
      </ul>
    </td>
  </tr>
</table>

---

### Tech Stack

<div align="center">

| Domain | Stack |
| :--- | :--- |
| **Languages & Core** | `Go`, `Rust`, `TypeScript`, `PHP`, `SQL`, `Bash` |
| **Networking & Protocols** | `QUIC / TLS 1.3`, `SPAKE2 (RFC 9382)`, `BLAKE3`, `mDNS`, `Axum`, `OTLP`, `MCP` |
| **Databases & Caching** | `PostgreSQL`, `SQLite (Pure-Go WAL)`, `Redis` |
| **Cloud & DevOps** | `Docker`, `Linux`, `Git`, `GitHub Actions`, `Make`, `Stripe API` |
| **Frontend & UI** | `Vue.js 3`, `HTMX`, `Tailwind CSS`, `Svelte`, `Laravel`, `Vite` |

</div>

---

<div align="center">

[Portfolio](https://yohann-hommet.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/yohann-hommet/) · [yohann.hommet@outlook.fr](mailto:yohann.hommet@outlook.fr)

</div>
