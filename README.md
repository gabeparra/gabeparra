## Gabriel Parra · Systems Integration, Backend & Applied AI

Software engineer in Orlando, FL, originally from Santiago, Chile (English and Spanish). Writing production software since 2014: ERP and inventory backends, identity workflows, internal web apps, and practical AI tooling. Currently Business Systems Analyst II at UCF Global.

[gabrielparra.dev](https://gabrielparra.dev) · [LinkedIn](https://linkedin.com/in/gabeparra) · [gabpar49@gmail.com](mailto:gabpar49@gmail.com) · Open to remote (US)

## Production Background

- **UCF Global (2025 to present):** Business Systems Analyst II building and running internal web applications, authentication workflows, and cross-system data integrations.
- **Repuestos Rojas (2017 to 2025, plus 2026 rollout):** Built the company-wide inventory system (Java, Python), Defontana ERP integration, and a C# WPF warehouse barcode/invoice scanner for a 50-person refrigeration parts distributor in Chile. In 2026, shipped a live 595-product WooCommerce store with an approval-gated WhatsApp AI assistant.
- **Comercial PYM (2014 to 2017):** Maintained and extended an in-house Python/MySQL POS and inventory system for a 50-person retailer, plus a Flask API feeding live stock to its storefront.

Most of my day-job and client code lives in private repos. The projects below rebuild the same integration and applied-AI patterns in the open alongside tools I run daily.

## Selected Projects

### Integration & Applied AI

- **[sync-ledger](https://github.com/gabeparra/sync-ledger):** Webhook ingestion and cross-system reconciliation engine for systems with no shared ID: HMAC checks, idempotency, transactional outbox, weighted entity matching, drift audits, retries, and a DLQ replay CLI. `Python` `FastAPI` `SQLAlchemy` `PostgreSQL`
- **[agent-gate](https://github.com/gabeparra/agent-gate):** Deterministic evaluation harness and MCP tool guardrail gate for LLM agents in CI. Catches fabricated citations, broken JSON, prompt injection, disallowed tool calls, and dishonest completions across mock CI profiles and live adapters. `Python` `MCP` `GitHub Actions`
- **[hermes-unity](https://github.com/gabeparra/hermes-unity):** Plugin letting Hermes Agent work in Unity 6 through a pinned, untrusted MCP server, documenting a batched-call approval gap. Paired with two open upstream PRs with regression tests in `NousResearch/hermes-agent` ([#151953](https://github.com/NousResearch/hermes-agent/pull/151953), [#156635](https://github.com/NousResearch/hermes-agent/pull/156635)). `Python` `MCP` `Unity 6`

### Systems & Tools

- **[control-center](https://github.com/gabeparra/control-center):** Android app for running my home lab (systemd, Docker, logs, vitals, Wake-on-LAN, DNS, remote terminals) with server-described UI extensions and a one-command synthetic demo server. `Kotlin` `Jetpack Compose` `FastAPI`
- **[rustyui](https://github.com/gabeparra/rustyui):** ComfyUI-compatible diffusion engine in Rust on candle (work in progress). Matches ComfyUI's output on tested SDXL graphs, finishes a cold start in half to two thirds the time on an RTX 4090, and frees GPU memory when idle. `Rust` `CUDA` `candle` `Vue 3`
- **[portbook](https://github.com/gabeparra/portbook):** Single-file, zero-dependency Python app for tracking machines, ports, connection maps, and tickets via a loopback web UI and local JSON storage. `Python` `Tailwind`

### Engineering Labs & More

- **[kafka-sync-pipeline](https://github.com/gabeparra/kafka-sync-pipeline):** Local Apache Kafka (KRaft) lab with transactional outbox publishing, Schema Registry contracts, idempotent PostgreSQL consumers, retry/DLQ topics, and real-broker crash tests. `Python` `Kafka` `PostgreSQL`
- **[tf-oidc-identity-stack](https://github.com/gabeparra/tf-oidc-identity-stack):** Local reference lab for AWS IAM OIDC federation and declarative Keycloak realm setup running end to end on LocalStack and Docker. `Terraform` `Keycloak` `LocalStack`
- **Also built:** [DockerOffline](https://github.com/gabeparra/DockerOffline) (air-gapped Ubuntu Docker installer) · [ChessCadets](https://github.com/gabeparra/ChessCadets) (UCF capstone, UE5/C++ Pulse engine bridge) · [Rolling with the Punches](https://github.com/gabeparra/rolling-with-the-punches) (Unity 6/C# team shooter, Android port) · [Margot AI](https://github.com/gabeparra/Margot.AI) (bilingual kids' word game) · Full portfolio at [gabrielparra.dev](https://gabrielparra.dev).

## Core Stack

- **Languages:** `Python` `TypeScript` `Java` `C#` `SQL` `Kotlin` `C++` `Rust` `Bash`
- **Backend & Data:** `FastAPI` `Flask` `Node.js` `React` `Astro` `PostgreSQL` `SQL Server` `MySQL` `SQLite`
- **Identity & Platform:** `Keycloak` `Entra ID` `Active Directory` `OAuth2 / OIDC` `LDAP` `Docker` `GitHub Actions` `GHCR` `nginx` `Linux` `AWS` `Azure`
- **Applied AI & Enterprise:** `MCP` `LLM Evals` `OpenAI / Anthropic / Azure AI Foundry` `llama.cpp` `PeopleSoft` `Slate` `ServiceNow` `WooCommerce`

B.S. Computer Science, University of Central Florida (2026) · Ingeniería en Informática, Duoc UC, Santiago, Chile (2017)
