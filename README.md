# Jurie "JustAGhosT" Smit

**AI & Platform Architect · Governance · DevEx**

I design and ship AI + cloud platforms in **high‑stakes, regulated and legacy‑heavy environments**  
(fintech, defence, citizen portals, regenerative agriculture).

---

## Core platform & tooling (code > claims)

These are the “this is how I actually build systems” repos.

### 🧠 Agentic / AI platforms

- **[cognitive-mesh](https://github.com/JustAGhosT/cognitive-mesh)**  
  Enterprise agent / LLM runtime with **RBAC, audit logging, policy‑as‑code** and Azure OpenAI + RAG integration.  
  _What it proves: AI platform architecture with governance and cost/safety seams._

- **[CognitiveMeshUI](https://github.com/JustAGhosT/CognitiveMeshUI)**  
  Next.js / TypeScript **UI & design system** for Cognitive Mesh – accessible components, Storybook, UX telemetry.  
  _What it proves: front‑end architecture for complex operational consoles._

- **[autopr-engine](https://github.com/JustAGhosT/autopr-engine)**  
  AI‑powered PR automation engine for GitHub: runs in CI, Docker or locally; multi‑agent review, platform detection, issue creation and quality gates.  
  _What it proves: DevEx tooling, CI/CD ecosystems, practical AI‑in‑the‑loop workflows._

### 🏗️ Cloud / infra / guardrails

- **[vv-iac](https://github.com/JustAGhosT/vv-iac)**  
  Azure landing‑zone **IaC with what‑if validation, policy‑as‑code and gated promotions** across environments.  
  _What it proves: infra‑as‑code, cost / compliance guardrails, safe change patterns._

- **[home-lab-setup](https://github.com/JustAGhosT/home-lab-setup)**  
  Multi‑platform homelab: Azure + Vercel + Netlify + AWS + GCP, P2S VPN, NAT, DNS, cert lifecycle, monitoring, cost reporting – wrapped as a PowerShell module.  
  _What it proves: hands‑on infra automation, networking, and “run it for real” instincts._

- **[crisis-unleashed-app](https://github.com/JustAGhosT/crisis-unleashed-app)**  
  Modular full‑stack starter (React + FastAPI) with auth, API, CI/CD, testing, and clean architecture. Originally built around a card‑game domain, now a **reference pattern** for full‑stack apps.  
  _What it proves: how I like to structure end‑to‑end products._

---

## Domain systems

Same architectural brain, very different problem spaces.

### 🛡️ Defence – PhoenixRooivalk

- **[PhoenixRooivalk](https://github.com/JustAGhosT/PhoenixRooivalk)**  
  Next‑generation **counter‑UAS defence platform**: modular VTOL mothership + interceptors + ground systems, operating **autonomously under full comms jamming** with 120–195 ms response times.  
  Rust + TypeScript monorepo with docs, deployment guides, responsible‑use and security policies.  
  _What it proves: taking AI + systems thinking into a hard real‑world domain with latency, safety and evidence requirements._

### 💸 DeFi risk & governance – VeritasVault (vv-*)

- **[vv-chain](https://github.com/JustAGhosT/vv-chain)**  
  Cross‑chain DeFi **risk intelligence infrastructure**: unified analytics for protocol health, TVL and systemic risk across EVM + Tezos, with stateless math libs and oracle adapters.

- **[vv-chain-services](https://github.com/JustAGhosT/vv-chain-services)**  
  Blockchain microservices (Ethereum, Tezos, Postgres, Fastify) powering VeritasVault’s **on‑chain identity, reputation and governance APIs.**

- **[vv-docs](https://github.com/JustAGhosT/vv-docs)**  
  Docusaurus/MDX documentation portal for VeritasVault – API refs, tutorials and design guidelines.

- **[vv-landing](https://github.com/JustAGhosT/vv-landing)**  
  Public marketing site for VeritasVault (Next.js + Tailwind) that ties the story together.

_What this bundle proves: I can design and document a full programmable‑finance stack – from risk math and microservices to docs and marketing – not just toy smart contracts._

### 🌱 Regenerative agriculture – farm systems

- **[farm-business-plan](https://github.com/JustAGhosT/farm-business-plan)**  
  “Agricultural Business Plan Template & Farm Management Tool” – a Next.js app plus rich docs to help farmers build, track and evolve business plans. Live at **farmplan.netlify.app**.

- **[zeeplan](https://github.com/JustAGhosT/zeeplan)**  
  Deep partnership / transformation plan for a **600 ha Bushveld farm**: regenerative 5‑year plan, stocking strategy, multi‑stream revenue model, ROI projections, risk analysis and earn‑in equity mechanics.

- **[pigpro](https://github.com/JustAGhosT/pigpro)**  
  TypeScript codebase that supports the pig‑production side of the broader farm stack (work in progress; description intentionally kept minimal here).

_What this bundle proves: I’m not just doing abstract infra – I’ll happily take the same modelling and system‑design habits into very physical, messy domains._

---

## Active work

- Lower‑latency, more explainable policy evaluation for agentic systems  
- Deterministic, forward‑compatible audit event schemas  
- Reducing false positives in AI‑assisted PR review (better semantic diff weighting & heuristics)  
- Safer infra promotion: collapsing pre‑merge what‑if + policy checks into a single gate

---

## Architecture (summary)

```mermaid
flowchart LR
  Client --> Runtime
  Runtime --> Governance
  Runtime --> Automation
  Automation --> Repo[(GitHub)]
  Runtime --> Delivery
  Delivery --> Cloud[(Azure)]
  Runtime --> Observability
