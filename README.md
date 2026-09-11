<div align="center">

# Yohann Hommet
### **Software Engineer** · Systems, Network Protocols & Agentic Observability

[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-0ea5e9?style=for-the-badge&logo=firefox-browser&logoColor=white)](https://yohann-hommet.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-YohannHommet-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YohannHommet)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yohann_Hommet-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yohann-hommet/)
[![X / Twitter](https://img.shields.io/badge/X-@Yohann__Dev-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/Yohann_Dev)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yohann.hommet@outlook.fr)

<br />

> *Designing zero-allocation data engines, secure peer-to-peer protocols, and developer-facing SaaS products for the autonomous agent era.*

<br />

</div>

---

### 🧠 About & Focus

I am a **Software Engineer** focused on low-level systems reliability, cryptographic networking protocols, and developer infrastructure for autonomous AI agents. I also build and operate developer-centric SaaS products.

- ⚙️ **Systems & Data Engines**: Author of [`walspool`](https://github.com/YohannHommet/walspool), an in-process, zero-allocation Write-Ahead Log (WAL) spooler designed as a high-throughput shock absorber for telemetry and event streaming.
- 🔒 **Encrypted Network Protocols**: Creator of [`wisp`](https://github.com/YohannHommet/wisp), a high-performance P2P transfer protocol written in Rust featuring QUIC transport, SPAKE2 mutual password-authenticated key exchange (RFC 9382), and streaming BLAKE3 hashing.
- 🤖 **Agentic AI Infrastructure**: Building [`argus`](https://github.com/YohannHommet/argus), an OTLP-native observability engine tracking subagent execution trees, inference token economics, and runtime decision graphs for autonomous coding tools.
- 🛠️ **Developer Tools & Micro-SaaS**: Creator of [**Unfurl**](https://unfurlit.vercel.app/) (an SSRF-safe Link Preview & Metadata API with Stripe billing) and [**LinkBounty**](https://github.com/YohannHommet/linkbounty) (a high-concurrency website link crawler in pure Go).
- 🔌 **Model Context Protocol (MCP)**: Author of production MCP servers ([`pg-lens-mcp`](https://github.com/YohannHommet/pg-lens-mcp), [`repo-lens-mcp`](https://github.com/YohannHommet/repo-lens-mcp)) and AI companion runtimes ([`buddy-patcher`](https://github.com/YohannHommet/buddy-patcher)).

---

### 🚀 Core Systems & AI Infrastructure

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/YohannHommet/walspool">walspool</a></h3>
      <p><em>The Zero-Allocation WAL Shock Absorber for Observability & Event Streaming</em></p>
      <p>High-throughput dual-engine Write-Ahead Log (WAL) spooler & OpenTelemetry ingestion hub built in pure Go. Buffers telemetry spikes to disk with microsecond latency to prevent OOM panics during upstream outages.</p>
      <p>
        <img src="https://img.shields.io/badge/Go_1.22+-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OTel" />
        <img src="https://img.shields.io/badge/Zero--Alloc-CCFF00?style=flat-square&logoColor=black&labelColor=16171C" alt="Zero-Alloc" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      </p>
      <ul>
        <li>Dual memory ring-buffer & disk segment engine</li>
        <li>Crash-resilient sub-millisecond recovery replay</li>
        <li><a href="https://yohannhommet.github.io/walspool/">Live Documentation & Benchmarks</a></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/YohannHommet/wisp">wisp</a></h3>
      <p><em>Zero-Cloud, High-Speed Encrypted P2P File Transfer Protocol</em></p>
      <p>Direct peer-to-peer file transfer engine in Rust utilizing QUIC and modern cryptography. Zero persistent state, zero third-party data access, and instant discovery.</p>
      <p>
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black" alt="Rust" />
        <img src="https://img.shields.io/badge/QUIC-TLS_1.3-00599C?style=flat-square" alt="QUIC" />
        <img src="https://img.shields.io/badge/SPAKE2-RFC_9382-success?style=flat-square" alt="SPAKE2" />
        <img src="https://img.shields.io/badge/BLAKE3-Verified-blue?style=flat-square" alt="BLAKE3" />
      </p>
      <ul>
        <li>Direct 1-RTT encrypted QUIC + ephemeral TLS handshake</li>
        <li>SPAKE2 password-authenticated key exchange</li>
        <li>Blind stateless rendezvous relay built on Axum</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>👁️ <a href="https://github.com/YohannHommet/argus">argus</a></h3>
      <p><em>OTLP-Native Coding Agent Observability Platform</em></p>
      <p>Dedicated telemetry backend & interactive dashboard designed for Claude Code and autonomous agent workflows. Ingests OTLP spans, tracks token burn rates, and visualizes subagent hierarchy trees.</p>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Vue.js_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres" />
      </p>
      <ul>
        <li>Real-time subagent call-graph & decision tracing</li>
        <li>Cost-per-task economics & latency breakdown</li>
        <li>PostgreSQL-backed time-series telemetry store</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔌 <a href="https://github.com/YohannHommet">Model Context Protocol & Dev Tooling</a></h3>
      <p><em>Autonomous Agent Ecosystem Tools</em></p>
      <p>Production MCP servers bridging AI coding agents with local infrastructure and data layers.</p>
      <p>
        <img src="https://img.shields.io/badge/MCP-Protocol-8A2BE2?style=flat-square" alt="MCP" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Claude_Code-E06535?style=flat-square" alt="Claude Code" />
      </p>
      <ul>
        <li><strong><a href="https://github.com/YohannHommet/pg-lens-mcp">pg-lens-mcp</a></strong>: PostgreSQL schema introspection & secure query execution for AI agents</li>
        <li><strong><a href="https://github.com/YohannHommet/repo-lens-mcp">repo-lens-mcp</a></strong>: Structural codebase indexing & fast context retrieval</li>
        <li><strong><a href="https://github.com/YohannHommet/buddy-patcher">buddy-patcher</a></strong>: Custom companion runtime for developer AI CLIs</li>
      </ul>
    </td>
  </tr>
</table>

---

### 📦 Developer Tools & SaaS Products

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔗 <a href="https://unfurlit.vercel.app/">Unfurl</a></h3>
      <p><em>Fast, SSRF-Safe Link Preview & Metadata Extraction API</em></p>
      <p>Developer-first micro-SaaS turning any URL into clean metadata JSON (title, description, social cards, icons). Built for production safety with manual redirect validation protecting internal subnets and cloud metadata endpoints.</p>
      <p>
        <img src="https://img.shields.io/badge/Live_Product-unfurlit.vercel.app-0ea5e9?style=flat-square" alt="Unfurl" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Stripe-Billing-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe" />
        <img src="https://img.shields.io/badge/Redis-Cache-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      </p>
      <ul>
        <li><strong>SSRF-safe on every hop</strong>: Prevents DNS rebinding and loopback probing</li>
        <li><strong>Multi-tier monetization</strong>: Free IP rate-limit & Stripe metered Pro API keys</li>
        <li><strong>High hit-rate caching</strong>: 24h Redis cache layer with <code>X-Cache</code> telemetry</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🎯 <a href="https://github.com/YohannHommet/linkbounty">LinkBounty</a></h3>
      <p><em>High-Concurrency Broken-Link Crawler & Diagnostic Engine</em></p>
      <p>Zero-friction link-checking engine written in pure Go. Crawls websites, verifies internal & outbound link health with pooled goroutines, and generates shareable diagnostic audits.</p>
      <p>
        <img src="https://img.shields.io/badge/Go_1.25+-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
        <img src="https://img.shields.io/badge/SQLite-WAL_Mode-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
        <img src="https://img.shields.io/badge/HTMX-SSR-3366CC?style=flat-square&logo=htmx&logoColor=white" alt="HTMX" />
        <img src="https://img.shields.io/badge/Zero_CGO-Compliant-success?style=flat-square" alt="Zero CGO" />
      </p>
      <ul>
        <li>Concurrent crawler with goroutine worker pool & anti-bot fallbacks</li>
        <li>SSRF-protected submission gate defeating DNS rebinding</li>
        <li>Single deployable binary with pure-Go SQLite persistence</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Stack & Architecture Competencies

<div align="center">

| Domain | Technologies & Standards |
| :--- | :--- |
| **Systems & Core Languages** | `Go`, `Rust`, `TypeScript`, `PHP`, `SQL`, `Bash` |
| **Networking & Cryptography** | `QUIC / TLS 1.3`, `SPAKE2 (RFC 9382)`, `BLAKE3`, `mDNS`, `Axum` |
| **Observability & Protocols** | `OpenTelemetry (OTLP)`, `Model Context Protocol (MCP)`, `Write-Ahead Logging (WAL)` |
| **Databases & Caching** | `PostgreSQL`, `SQLite (Pure-Go WAL)`, `Redis` |
| **Cloud, DevOps & Tooling** | `Docker`, `Linux`, `Git`, `GitHub Actions`, `Make`, `Stripe API` |
| **Application & Interface** | `Vue.js 3`, `HTMX`, `Tailwind CSS`, `Svelte`, `Laravel`, `Vite` |

</div>

---

### 📈 Activity & Streak

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=YohannHommet&theme=github-dark-dimmed&hide_border=true" alt="GitHub Streak" />
</div>

---

<div align="center">

<sub>Crafting robust software from low-level byte buffers to distributed agent architectures.</sub>

</div>
