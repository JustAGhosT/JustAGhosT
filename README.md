# Jurie "JustAGhosT" Smit

**Systems Engineer & AI Architect**  
Regulated platforms • Agentic AI • Rust/TypeScript monorepos • DeFi & regenerative agriculture

> **Currently:** CTO (part-time) at [Phoenix VC](https://github.com/phoenixvc). **Open to remote .NET / architecture contracts from July 2026.**  Gauteng, South Africa · [LinkedIn](https://www.linkedin.com/in/juriesmit) · [phoenixvc.tech](https://phoenixvc.tech)

I work where **AI, legacy systems, and real-world risk** collide:

- Agent/LLM platforms with **governance, cost & telemetry baked in**
- **DeFi / chain** systems that have actual risk math, not just vibes
- Farm & land systems where **business plans, software, and soil** line up
- Delivery / IaC / PR automation that makes all of this **repeatable**

## Where the current work lives

Most active work now happens in the organisations:

- **[Phoenix VC](https://github.com/phoenixvc)** — AI platforms for **storytelling, enterprise intelligence and developer ops** (TypeScript · .NET · Rust · Azure). Active repos: [`cognitive-mesh`](https://github.com/phoenixvc/cognitive-mesh) (agent/LLM platform, .NET 10), [`retort`](https://github.com/phoenixvc/retort) (AI-orchestration framework), [`baton`](https://github.com/phoenixvc/baton) (human+agent task graph, MCP), [`sluice`](https://github.com/phoenixvc/sluice) (AI gateway on Azure Container Apps), [`codeflow-engine`](https://github.com/phoenixvc/codeflow-engine) (multi-agent PR automation), [`deck`](https://github.com/phoenixvc/deck) (Tauri desktop ops). **Mystira** — interactive storytelling app for children — is also a Phoenix VC product (live at [mystira.app](https://mystira.app); repo private).
- **[NeuralLiquid](https://github.com/neuralliquid)** — the applied-product brand `cognitive-mesh` is relaunching as: [`house-of-veritas`](https://github.com/neuralliquid/house-of-veritas) (estate management — documents, e-signatures, payroll, compliance), [`convolens`](https://github.com/neuralliquid/convolens) (chat analyzer), [`omnipost`](https://github.com/neuralliquid/omnipost).
- **[Nexamesh](https://github.com/Nexamesh)** — counter-UAS defence simulation: [`nexamesh-core`](https://github.com/Nexamesh/nexamesh-core) (Rust/Axum, Next.js, Leptos/WASM, Tauri, Solana). *(This is the evolution of the earlier PhoenixRooivalk work.)*

If you’re skimming, start with:  
[`cognitive-mesh`](https://github.com/phoenixvc/cognitive-mesh), [`retort`](https://github.com/phoenixvc/retort), [`codeflow-engine`](https://github.com/phoenixvc/codeflow-engine),  
[`nexamesh-core`](https://github.com/Nexamesh/nexamesh-core),  
[`farm-business-plan`](https://github.com/JustAGhosT/farm-business-plan), [`zeeplan`](https://github.com/JustAGhosT/zeeplan), [`pigpro`](https://github.com/JustAGhosT/pigpro),  
[`vv-landing`](https://github.com/JustAGhosT/vv-landing), [`vv-iac`](https://github.com/JustAGhosT/vv-iac).

---

## Core themes

- **Cognitive Mesh & human–AI collaboration**  
  Orchestrating tools/agents with RBAC, audit, policy-as-code, and observability. Built to survive regulated environments, not just “demo calls”.

- **VeritasVault – DeFi risk & chain governance**  
  Chain contracts, services, landing, and docs wired together via docs + IaC so the whole surface is governable and explainable.

- **Nexamesh / counter‑UAS – Rust + TS platform**  
  A serious monorepo (Rust + TypeScript + Next.js + Tauri, Turborepo + Cargo) for a c‑UAS evidence & control stack with dual-chain anchoring.

- **Regenerative agriculture & “skin‑in‑the‑game” design**  
  Multi-year farm plans, financial models, and working software aimed at cash flows, not dribbble screenshots.

- **Delivery, infra & governance**  
  IaC, policy gates, what‑if validation, PR automation, and template repos that bake in tests, type-checking, and CI.

---

## 🧠 Cognitive Mesh & DevEx AI

### `cognitive-mesh` – agentic AI platform (.NET)

**Repo:** https://github.com/phoenixvc/cognitive-mesh

- **Stack:**  
  - Backend: **C# / .NET 10** service  
  - Targets: Azure OpenAI, RAG integrations  
  - Surroundings: RBAC, audit logging, policy-as-code, cost/usage observability  
- **What it shows about me:**  
  - I treat “agents” as production services: layered architecture, least-privilege, and explicit governance instead of ad-hoc scripts.
  - Hooks for eval and telemetry, not just “call the model and hope”.

*(Its governance-first UI, CognitiveMeshUI, and the NeuralLiquid relaunch products build on this platform — repos currently private.)*

---

### `codeflow-engine` – AI-assisted PR automation (Python + Docker + CI)

**Repo:** https://github.com/phoenixvc/codeflow-engine  *(continues the earlier, now-archived `autopr-engine`)*

- **Stack:**  
  - Core: **Python** package, multi-agent  
  - Supports: Docker, GitHub Action / Marketplace app  
- **What it does:**
  - Analyzes PRs, runs static checks, opens issues, and coordinates multi-agent review flows.
  - Designed to run locally, in CI, or as a GitHub app.
- **Why it matters:**  
  - AI applied to **DevEx and governance**: quality gates, automated issue creation, and multi-agent workflows instead of another “chat in your IDE” toy.

---

## 🧱 VeritasVault (vv-*) – DeFi risk & infra slice

VeritasVault is a full surface: contracts, services, landing, and IaC.

- **[`vv`](https://github.com/JustAGhosT/vv)** – institutional DeFi analytics & dual-brand trading platform (C#/TS).
- **[`vv-chain`](https://github.com/JustAGhosT/vv-chain)** – cross-chain DeFi risk intelligence (Solidity).
- **[`vv-chain-services`](https://github.com/JustAGhosT/vv-chain-services)** – on-chain identity, reputation & governance APIs (Ethereum, Tezos, Postgres, Fastify).
- **[`vv-landing`](https://github.com/JustAGhosT/vv-landing)** – public marketing site (Next.js + React + Tailwind), deploys to VeritasVault.ai.
- **[`vv-iac`](https://github.com/JustAGhosT/vv-iac)** – Azure IaC (Bicep/Terraform) with what-if validation, policy-as-code and gated promotions.
- **[`vv-dev-tools`](https://github.com/JustAGhosT/vv-dev-tools)** – shared dev tooling and workspace config across the VV repos.

These show how I think about **product as a system**: contracts → services → docs → infra → governance.

---

## 🛰 Nexamesh – Rust + TS counter‑drone platform

**Repo:** https://github.com/Nexamesh/nexamesh-core

A serious **counter‑UAS defence monorepo**, not just a slide deck (evolved from the earlier PhoenixRooivalk).

- **Monorepo & tooling:** Turborepo + **pnpm** + Cargo workspace; ESLint, Prettier, Husky, Clippy, cspell; CI via GitHub Actions, CodeQL.
- **Apps:** Docusaurus docs; Next.js marketing (threat simulator, ROI calculator); **Rust (Axum)** API; Rust chain keeper; Rust evidence CLI.
- **Rust crates:** core evidence logging; dual-chain anchoring (Solana + Etherlink); address validation.
- **Why it matters:** I can take a **hardware-adjacent, security-sensitive** domain and turn it into a properly structured Rust+TS platform — docs, UI, API, blockchain layers, and dev tooling in one place.

Yes, **Rust** is very much part of my current workflow.

---

## 🌱 Farms, land & “skin‑in‑the‑game” systems

These aren’t theory projects. They sit on **real land, real livestock, and real partners**.

- **[`farm-business-plan`](https://github.com/JustAGhosT/farm-business-plan)** – Next.js farm-planning app: structured docs, financial models, ongoing planning.
- **[`zeeplan`](https://github.com/JustAGhosT/zeeplan)** – Zeerust farm operations plan: 5‑year transformation, equity splits, ROI analysis, risk mitigation — performance-based, zero-cash-entry equity structures documented like a system design.
- **[`pigpro`](https://github.com/JustAGhosT/pigpro)** – livestock marketplace for South African farmers (React/TypeScript): buy and sell pigs, cattle and agricultural products.
- **[`goat-farming-guide`](https://github.com/JustAGhosT/goat-farming-guide)** – content platform: **C# Azure Functions** + Cosmos DB backend, Next.js frontend, Bicep infra, Contentful CMS.

---

## 🧰 Templates, homelab & supporting systems

- **[`crisis-unleashed-app`](https://github.com/JustAGhosT/crisis-unleashed-app)** – modular full‑stack starter (React/Next.js + **Python FastAPI**), auth, API, CI, tests, clean architecture.
- **[`home-lab-setup`](https://github.com/JustAGhosT/home-lab-setup)** – Azure homelab in **PowerShell**: P2S VPN, NAT, DNS, certificate lifecycle, monitoring/alerts, cost guardrails.

---

## If you’re evaluating me

- **AI / agent platforms & DevEx:** [`cognitive-mesh`](https://github.com/phoenixvc/cognitive-mesh), [`retort`](https://github.com/phoenixvc/retort), [`codeflow-engine`](https://github.com/phoenixvc/codeflow-engine)
- **DeFi / chain + governance:** [`vv`](https://github.com/JustAGhosT/vv), [`vv-chain`](https://github.com/JustAGhosT/vv-chain), [`vv-landing`](https://github.com/JustAGhosT/vv-landing), [`vv-iac`](https://github.com/JustAGhosT/vv-iac)
- **“Can this person handle messy reality?”:** [`zeeplan`](https://github.com/JustAGhosT/zeeplan), [`farm-business-plan`](https://github.com/JustAGhosT/farm-business-plan), [`pigpro`](https://github.com/JustAGhosT/pigpro), [`goat-farming-guide`](https://github.com/JustAGhosT/goat-farming-guide)
- **Security / Rust-heavy & hardware-adjacent:** [`nexamesh-core`](https://github.com/Nexamesh/nexamesh-core)
- **Engineering quality & scaffolding:** [`crisis-unleashed-app`](https://github.com/JustAGhosT/crisis-unleashed-app), [`home-lab-setup`](https://github.com/JustAGhosT/home-lab-setup)

---

## Tech & practices (short version)

**Languages & runtimes**

- **C# / .NET** – `cognitive-mesh` (.NET 10), Azure Functions APIs (`goat-farming-guide`, `vv`)
- **TypeScript / JavaScript** – Next.js, React, Node, monorepos (Turborepo, pnpm, Vite)
- **Python** – FastAPI backends, automation tools, CLI, PR automation (`codeflow-engine`, `crisis-unleashed-app`)
- **Rust** – API services, chain keepers, CLI & core crates in `nexamesh-core`

**Cloud / infra**

- Azure (Functions, Cosmos DB, Container Apps, Static Web Apps, VNets/VPNs, DNS); some AWS
- Netlify / Vercel for marketing & doc sites
- IaC via Bicep / ARM / Terraform (`vv-iac`, `goat-farming-guide`), plus homelab PowerShell

**Architecture & delivery**

- Monorepos with pnpm / Turborepo where it makes sense
- Clean boundaries between frontend / backend / docs / infra
- CI/CD with GitHub Actions: tests, linting, type-checking, deploys
- Policy-as-code orientation, and eval/telemetry hooks on AI systems

---

- LinkedIn: [linkedin.com/in/juriesmit](https://www.linkedin.com/in/juriesmit)  
- Phoenix VC site: [phoenixvc.tech](https://phoenixvc.tech)  
- GitHub: you’re here – issues/PRs are welcome on anything above.
