# Jurie "JustAGhosT" Smit

**Systems Engineer & AI Architect**  
Regulated platforms • Agentic AI • Rust/TypeScript monorepos • DeFi & regenerative agriculture

I work where **AI, legacy systems, and real-world risk** collide:

- Agent/LLM platforms with **governance, cost & telemetry baked in**
- **DeFi / chain** systems that have actual risk math, not just vibes
- Farm & land systems where **business plans, software, and soil** line up
- Delivery / IaC / PR automation that makes all of this **repeatable**

If you’re skimming, start with:  
[`cognitive-mesh`](https://github.com/JustAGhosT/cognitive-mesh), [`CognitiveMeshUI`](https://github.com/JustAGhosT/CognitiveMeshUI),  
[`autopr-engine`](https://github.com/JustAGhosT/autopr-engine),  
[`PhoenixRooivalk`](https://github.com/JustAGhosT/PhoenixRooivalk),  
[`farm-business-plan`](https://github.com/JustAGhosT/farm-business-plan), [`zeeplan`](https://github.com/JustAGhosT/zeeplan), [`pigpro`](https://github.com/JustAGhosT/pigpro),  
[`vv-docs`](https://github.com/JustAGhosT/vv-docs), [`vv-landing`](https://github.com/JustAGHosT/vv-landing).

---

## Core themes

- **Cognitive Mesh & human–AI collaboration**  
  Orchestrating tools/agents with RBAC, audit, policy-as-code, and observability. Built to survive regulated environments, not just “demo calls”.

- **VeritasVault – DeFi risk & chain governance**  
  Chain contracts, services, landing, and docs wired together via docs + IaC so the whole surface is governable and explainable. :contentReference[oaicite:0]{index=0}  

- **PhoenixRooivalk – Rust + TS counter‑drone platform**  
  A serious monorepo (Rust + TypeScript + Next.js + Docusaurus, Turborepo) for a c‑UAS evidence & control stack with dual-chain anchoring. :contentReference[oaicite:1]{index=1}  

- **Regenerative agriculture & “skin‑in‑the‑game” design**  
  Multi-year farm plans, financial models, and working software aimed at cash flows, not dribbble screenshots. :contentReference[oaicite:2]{index=2}  

- **Delivery, infra & governance**  
  IaC, policy gates, what‑if validation, PR automation, and template repos that bake in tests, type-checking, and CI.

---

## 🧠 Cognitive Mesh & DevEx AI

### `cognitive-mesh` – agentic AI platform (.NET)

**Repo:** https://github.com/JustAGhosT/cognitive-mesh :contentReference[oaicite:3]{index=3}  

- **Stack:**  
  - Backend: **C# / .NET 9** service  
  - Targets: Azure OpenAI, RAG integrations  
  - Surroundings: RBAC, audit logging, policy-as-code, cost/usage observability  
- **What it shows about me:**  
  - I treat “agents” as production services: layered architecture, least-privilege, and explicit governance instead of ad-hoc scripts.
  - Hooks for eval and telemetry, not just “call the model and hope”.

---

### `CognitiveMeshUI` – governance-first AI UI (Next.js / TS)

**Repo:** https://github.com/JustAGhosT/CognitiveMeshUI :contentReference[oaicite:4]{index=4}  

- **Stack:**  
  - **Next.js + React + TypeScript**  
  - Tailwind, Storybook, Style Dictionary  
- **Focus:**  
  - Token-driven component library  
  - Screens for agents, tools, audit events, and cost telemetry  
- **Value:** Front-end architecture that treats AI as **infrastructure**: observable, inspectable, and explainable.

---

### `autopr-engine` – AI-assisted PR automation (Python + Docker + CI)

**Repo:** https://github.com/JustAGhosT/autopr-engine :contentReference[oaicite:5]{index=5}  

- **Stack:**  
  - Core: **Python 3.8+** package (published to PyPI)  
  - Supports: Docker, GitHub Action / Marketplace app  
  - Extras: Small TypeScript + PowerShell utilities  
- **What it does:**
  - Analyzes PRs, runs static checks, opens issues, and coordinates multi-agent review flows.
  - Designed to run locally, in CI, or as a GitHub app.
- **Why it matters:**  
  - It’s AI applied to **DevEx and governance**: quality gates, automated issue creation, platform detection, and multi-agent workflows instead of another “chat in your IDE” toy.

---

## 🧱 VeritasVault (vv-*) – DeFi risk & infra slice

VeritasVault is a full surface: contracts, services, landing, docs, and IaC. `vv-docs` is the knowledge hub aggregating contract, service, and infra docs across the VV repos. :contentReference[oaicite:6]{index=6}  

### `vv-docs` – Docusaurus / MDX docs hub

**Repo:** https://github.com/JustAGhosT/vv-docs :contentReference[oaicite:7]{index=7}  

- **Stack:**  
  - **Docusaurus + MDX**, Node, Yarn  
  - Mermaid diagrams, Algolia DocSearch  
- **Role:**  
  - Aggregates docs from: `vv-chain`, `vv-chain-services`, `vv`, `vv-frontend`, `vv-gamification`, `vv-dev-tools`, `cognitive-mesh`, etc.  
  - Includes auto-sync pipelines via GitHub Actions.
- **Signal:** I actually implement **unified context**: code, infra, and docs wired into one documentation hub.

---

### `vv-landing` – Next.js marketing surface

**Repo:** https://github.com/JustAGhosT/vv-landing :contentReference[oaicite:8]{index=8}  

- **Stack:**  
  - **Next.js + React + TypeScript**  
  - Tailwind CSS, CSS modules  
  - CI/CD with tests, linting, type-checks and deploys to `VeritasVault.net`.  
- **Role:**  
  - The public marketing site for VeritasVault.ai.  
  - Uses structured types and components to keep product messaging and docs aligned.

---

### `vv-iac` & friends (infra & ecosystem)

Some VV repos are more infra and platform-facing:

- **`vv-iac`** – Azure IaC for VeritasVault (Bicep/ARM, policy definitions, deployments).  
- **`vv-*` family referenced in `vv-docs`** – chain services, gamification, frontend, dev-tools, etc, documented from a single hub. :contentReference[oaicite:9]{index=9}  

These together show how I think about **product as a system**: contracts → services → docs → infra → governance.

---

## 🛰 PhoenixRooivalk – Rust + TS counter‑drone platform

**Repo:** https://github.com/JustAGhosT/PhoenixRooivalk :contentReference[oaicite:10]{index=10}  

PhoenixRooivalk is a serious **counter‑UAS defense monorepo**, not just a slide deck.

- **Monorepo & tooling:**  
  - Turborepo + **pnpm** workspace  
  - Linting & quality: ESLint, Prettier, Husky, Clippy, cspell  
  - CI: GitHub Actions, CodeQL, Netlify deploys
- **Apps:**  
  - `apps/docs` — **Docusaurus** technical documentation  
  - `apps/marketing` — **Next.js 14** marketing site (threat simulator, ROI calculator, interactive demos)  
  - `apps/api` — **Rust (Axum)** API server  
  - `apps/keeper` — Rust chain keeper  
  - `apps/evidence-cli` — Rust CLI for evidence flows
- **Rust crates:**  
  - `crates/evidence` — core evidence logging  
  - `crates/anchor-solana` / `anchor-etherlink` — dual-chain anchoring (Solana + Etherlink)  
  - `crates/address-validation` — address safety checks
- **Why it matters:**  
  - It shows I can take a **hardware-adjacent, security-sensitive** domain and turn it into a properly structured Rust+TS platform: docs, UI, API, blockchain layers, and dev tooling in one place.

Yes, **Rust** is very much part of my current workflow.

---

## 🌱 Farms, land & “skin‑in‑the‑game” systems

These aren’t theory projects. They sit on **real land, real livestock, and real partners**.

### `farm-business-plan` – Next.js farm planning app

**Repo:** https://github.com/JustAGhosT/farm-business-plan :contentReference[oaicite:11]{index=11}  

- **Stack:**  
  - **Next.js** application (Node/TS)  
  - Tailwind CSS, Jest tests  
  - CI/CD with GitHub Actions, deployed to Netlify (`farmplan.netlify.app`)  
- **Role:**  
  - Agricultural business plan template & farm management tool.  
  - Mixes structured docs, financial models, and a web app for ongoing planning.

---

### `zeeplan` – Zeerust partnership & ROI model

**Repo:** https://github.com/JustAGhosT/zeeplan :contentReference[oaicite:12]{index=12}  

- **Stack:**  
  - TypeScript-heavy Next.js-style codebase (Next config + TS, ~70% TS, ~29% CSS).  
- **Content:**  
  - Full partnership proposal (Zeerust, SA): current state, 5‑year transformation, equity splits, ROI analysis, risk mitigation, version history.  
- **Why it matters:**  
  - Shows how I negotiate & design **performance-based, zero-cash entry equity structures** and document them like a system design.

---

### `pigpro` – monorepo for pig production ops

**Repo:** https://github.com/JustAGhosT/pigpro :contentReference[oaicite:13]{index=13}  

- **Stack:**  
  - **Full-stack TypeScript** monorepo  
  - Vite-based frontend, Vitest tests, Tailwind config, Node backend folder structure  
- **Role:**  
  - Domain-driven structure for pig production operations.  
- **Signal:**  
  - I treat farm ops as a proper software domain: typed modules, tests, shared packages, not a one-off spreadsheet.

---

### `goat-farming-guide` – API + Next.js + Azure infra

**Repo:** https://github.com/JustAGhosT/goat-farming-guide :contentReference[oaicite:14]{index=14}  

- **Stack:**  
  - Backend: **C# Azure Functions** API using Azure Cosmos DB  
  - Frontend: **Next.js + React**  
  - Infra: `infra/bicep` for Azure resources; Contentful headless CMS integration  
- **Purpose:**  
  - Comprehensive goat farming knowledge site: health, feeding, economics, mistakes, investor info, DIY milking stand, etc.  
- **Why it matters:**  
  - Shows how I combine **.NET cloud functions + TS frontend + headless CMS + Bicep** to ship a content-heavy domain product.

---

## 🧰 Templates, homelab & supporting systems

### `crisis-unleashed-app` – full‑stack starter (React + FastAPI)

**Repo:** https://github.com/JustAGhosT/crisis-unleashed-app :contentReference[oaicite:15]{index=15}  

- **Stack:**  
  - Frontend: `frontend-next` – **React / Next.js + TypeScript + Tailwind**  
  - Backend: `backend` – **Python FastAPI**  
  - Tooling: Docker (frontend/backend), pnpm workspace, Jest, Pyright, k6 perf tests
- **Role:**  
  - Modular full‑stack template with auth, API, tests, CI, clean architecture.  
  - Also doubles as a digital TCG / chain‑integrated concept to keep it interesting.

---

### `home-lab-setup` – Azure homelab (PowerShell)

**Repo:** https://github.com/JustAGhosT/home-lab-setup  

- **Stack:**  
  - **PowerShell** automation  
  - Azure networking + infra  
- **Scope:**  
  - P2S VPN, NAT, DNS, certificate lifecycle, monitoring/alerts, cost guardrails (as per repo summary).  
- **Why it matters:**  
  - Shows my defaults for **secure, observable cloud networking** and cost control in a small but realistic environment.

---

## If you’re evaluating me

### For AI / agent platforms & DevEx

- **Platform:** [`cognitive-mesh`](https://github.com/JustAGhosT/cognitive-mesh)  
- **Governance UI:** [`CognitiveMeshUI`](https://github.com/JustAGhosT/CognitiveMeshUI)  
- **DevEx / CI automation:** [`autopr-engine`](https://github.com/JustAGhosT/autopr-engine)

### For DeFi / chain + governance

- **Docs hub:** [`vv-docs`](https://github.com/JustAGHosT/vv-docs)  
- **Public surface:** [`vv-landing`](https://github.com/JustAGHosT/vv-landing)  
- **Infra & supporting repos:** `vv-iac`, `vv-chain`, `vv-chain-services`, `vv-gamification`, `vv-frontend`, `vv-dev-tools` (all wired together via `vv-docs`). :contentReference[oaicite:16]{index=16}  

### For “can this person handle messy reality?”

- Regenerative farm partnership & ROI structure: [`zeeplan`](https://github.com/JustAGHosT/zeeplan)  
- Crop-agnostic farm planning app: [`farm-business-plan`](https://github.com/JustAGHosT/farm-business-plan)  
- Operational pig production system: [`pigpro`](https://github.com/JustAGHosT/pigpro)  
- Goat farming API + content platform: [`goat-farming-guide`](https://github.com/JustAGHosT/goat-farming-guide)  

### For security / Rust-heavy & hardware-adjacent work

- Full Rust + TS monorepo with docs, marketing, API & chain anchoring:  
  [`PhoenixRooivalk`](https://github.com/JustAGHosT/PhoenixRooivalk)

### For general engineering quality & scaffolding

- Full-stack template (React + FastAPI, CI, tests, perf tooling):  
  [`crisis-unleashed-app`](https://github.com/JustAGHosT/crisis-unleashed-app)  
- Infra defaults & Azure plumbing:  
  [`home-lab-setup`](https://github.com/JustAGHosT/home-lab-setup)

If you only have 10 minutes, skim the READMEs in:

- `cognitive-mesh`  
- `PhoenixRooivalk`  
- `vv-docs` / `vv-landing`  
- `farm-business-plan`  
- `zeeplan`  
- `pigpro`

---

## Tech & practices (short version)

**Languages & runtimes**

- **TypeScript / JavaScript** – Next.js, React, Node, monorepos (Turborepo, pnpm, Vite) :contentReference[oaicite:17]{index=17}  
- **Python** – FastAPI backends, automation tools, CLI, PR automation (`autopr-engine`, `crisis-unleashed-app`) :contentReference[oaicite:18]{index=18}  
- **C# / .NET** – `cognitive-mesh`, Azure Functions API (`goat-farming-guide`) :contentReference[oaicite:19]{index=19}  
- **Rust** – API services, chain keepers, CLI & core crates in `PhoenixRooivalk` :contentReference[oaicite:20]{index=20}  

**Cloud / infra**

- Azure (Functions, Cosmos DB, Static Web Apps, VNets/VPNs, DNS) :contentReference[oaicite:21]{index=21}  
- Netlify, Vercel and static exports for marketing / doc sites :contentReference[oaicite:22]{index=22}  
- IaC via Bicep / ARM (`goat-farming-guide`, `vv-iac`), plus homelab PowerShell.

**Architecture & delivery**

- Monorepos with pnpm / Turborepo where it makes sense  
- Clean boundaries between frontend/backend/docs/infra  
- CI/CD with GitHub Actions: tests, linting, type-checking, deploys on most public-facing repos :contentReference[oaicite:23]{index=23}  
- Policy-as-code orientation (vv‑*, home-lab, vv-iac), and eval/telemetry hooks on AI systems.

---

- LinkedIn: [linkedin.com/in/juriesmit](https://www.linkedin.com/in/juriesmit)  
- Phoenix VC site: [phoenixvc.tech](https://phoenixvc.tech)  
- GitHub: you’re here – issues/PRs are welcome on anything above.
