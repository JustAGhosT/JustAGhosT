# Jurie "JustAGHosT" Smit

**Systems Engineer & AI Architect**  
Regulated platforms • Agentic AI • DeFi risk infra • Regenerative agriculture

I sit where **AI, legacy systems, and real-world risk** collide:

- Agent / LLM platforms with **governance and telemetry baked in**
- **Crypto / DeFi** infra with actual risk math, not hype
- Farm & land systems where **business plans, code, and dirt** line up
- Delivery pipelines that make all of the above **repeatable**

---

## If you only click a few links

- 🧠 AI platform: [`cognitive-mesh`](https://github.com/JustAGhosT/cognitive-mesh)  
- 🛰 Defence: [`PhoenixRooivalk`](https://github.com/JustAGhosT/PhoenixRooivalk)  
- 🌱 Real-world “skin in the game”: [`zeeplan`](https://github.com/JustAGhosT/zeeplan)  

---

## Core themes

- **Cognitive Mesh & Human–AI collaboration**  
  Orchestrating tools/agents with RBAC, audit, policy-as-code, and observability.

- **VeritasVault – DeFi risk & chain governance**  
  Stateless-first smart contracts, cross-chain services, and policy/IaC for regulated‑ish crypto.

- **Regenerative agriculture & “skin-in-the-game” design**  
  Business plans, financial models, and actual farm systems (Zeerust, Regal Roots, pig production).

- **Counter‑UAS & safety‑critical design**  
  PhoenixRooivalk: modular counter‑drone defence with edge autonomy and dual‑chain evidence trails.

- **Delivery, infra & governance**  
  IaC, what-if validation, policy gates, PR automation, and clean app templates.

---

## 🧠 Cognitive Mesh – agentic AI platform

- **[`cognitive-mesh`](https://github.com/JustAGhosT/cognitive-mesh)**  
  Enterprise agent/LLM platform with:
  - Layered governance: RBAC, audit logging, policy-as-code  
  - Azure OpenAI + RAG ready, cost/usage observability  
  - Hooks for eval frameworks and tool usage tracking  
  _Shows: how I think about AI platforms when compliance and ops actually matter._

- **[`CognitiveMeshUI`](https://github.com/JustAGHosT/CognitiveMeshUI)**  
  Next.js / TypeScript UI for Cognitive Mesh:
  - Token-driven design, Storybook, accessibility focus  
  - UX for agents, tools, audit events & costs  
  - Telemetry wired at the UI layer  
  _Shows: front‑end architecture, design systems, and UX for AI governance._

- **[`autopr-engine`](https://github.com/JustAGHosT/autopr-engine)**  
  AI-assisted PR automation engine:
  - Runs in CI, Docker, or locally  
  - Analyzes PRs and posts actionable reviews  
  - Provider-agnostic, extensible via plugins  
  _Shows: “AI in the loop” DevEx tooling, not just chatbots._

---

## 🧱 VeritasVault – vv-* cluster (DeFi risk & infra)

Core VeritasVault repos live in the `vv-*` family:

- **[`vv-chain`](https://github.com/JustAGHosT/vv-chain)** – Solidity smart contracts  
  - Stateless-first math libraries for TVL, risk scores, health factors  
  - Oracle adapters, cross-chain encoders, and facades  
  - Monorepo layout with DSL + compiler hooks for multi-chain targets  
  _Shows: DeFi risk math, stateless architecture, and contract-level design discipline._

- **[`vv-chain-services`](https://github.com/JustAGHosT/vv-chain-services)** – microservices  
  - Ethereum/Tezos microservices (Fastify, Postgres, etc.)  
  - Identity, reputation, and governance APIs  
  - Devcontainer + workflows for consistent local/dev/prod setups  
  _Shows: how I wrap chain logic in sane services + ops._

- **[`vv-iac`](https://github.com/JustAGHosT/vv-iac)** – infrastructure-as-code  
  - Azure + Terraform/Bicep with `what-if` validation  
  - Policy-as-code, gated promotions, and cost guardrails  
  _Shows: IaC with governance and change risk front-and-centre._

- **[`vv-docs`](https://github.com/JustAGHosT/vv-docs)** – documentation portal  
  - Docusaurus/MDX docs for APIs, concepts, and design guidelines  
  - Structured for both humans and AI tools to consume  
  _Shows: how I structure unified context across code, docs, and ops._

- **Also part of the VV slice** (shorter descriptions):
  - **[`vv-landing`](https://github.com/JustAGHosT/vv-landing)** – Next.js/Tailwind public marketing site  
  - **[`vv-game-suite`](https://github.com/JustAGHosT/vv-game-suite)** – WebGL DeFi game framework for risk/governance simulations  
  - **[`vv-dev-tools`](https://github.com/JustAGHosT/vv-dev-tools)** – shared dev tooling and workspace config  
  - **[`vv-auth`](https://github.com/JustAGHosT/vv-auth)** – auth-related scripts/infra glue  

_Together, the vv-* repos show how I design a **full stack of chain + services + infra + docs** for a real product, not a toy._

---

## 🌱 Farms, land & “skin-in-the-game” systems

This is where the architecture has to survive **cows, pigs, weather, and family politics.**

- **[`zeeplan`](https://github.com/JustAGHosT/zeeplan)** – Zeerust regenerative partnership  
  - Next.js-based site + a full partnership proposal  
  - Multi-year regenerative plan, financial projections, risk modeling  
  - Performance-based equity structure and real ROI numbers  
  _Shows: applied systems thinking, finance, and negotiation embedded in docs + code._

- **[`farm-business-plan`](https://github.com/JustAGHosT/farm-business-plan)**  
  - Supporting repo for broader farm planning and modeling  
  _Shows: how I structure business logic and documentation around a real asset._

- **[`pigpro`](https://github.com/JustAGHosT/pigpro)**  
  - Full-stack TypeScript monorepo for pig production operations  
  - `backend/api`, `packages/domain`, DIY/public UI surface  
  - Docker, Vite, Vitest, Tailwind  
  _Shows: domain-driven modules, monorepo hygiene, and agri-ops as a proper software domain._

- **[`RegalRoots`](https://github.com/JustAGHosT/RegalRoots)**  
  - Astro + Svelte + React static site for a local farm  
  - Public marketing site + business docs in one repo  
  _Shows: how I connect web presence, tech stack and business artefacts._

(If you want to see how serious I am about this slice, read the `README.md` and plan docs inside `zeeplan`.)

---

## 🛰 PhoenixRooivalk – counter‑drone system concept

- **[`PhoenixRooivalk`](https://github.com/JustAGHosT/PhoenixRooivalk)**  
  Business/technical plan for a modular drone-defence system:
  - RF jamming, GPS spoofing, physical countermeasures  
  - Clear market segmentation (government, events, private sector)  
  - Financial projections, next steps, and GitHub Pages site  
  _Shows: concept-to-business-plan thinking in a security / hardware‑adjacent domain._

---

## 🧰 Supporting infra & templates

- **[`crisis-unleashed-app`](https://github.com/JustAGHosT/crisis-unleashed-app)**  
  React + FastAPI full‑stack template with auth, tests, CI/CD and clean architecture. Good view of my default app skeleton.

- **[`home-lab-setup`](https://github.com/JustAGHosT/home-lab-setup)**  
  Azure homelab via PowerShell (P2S VPN, DNS, cert lifecycle, monitoring, and cost guardrails). Shows my infra/ops defaults.

---

## If you’re evaluating me

**For AI / agentic platforms**

- Code: [`cognitive-mesh`](https://github.com/JustAGHosT/cognitive-mesh), [`CognitiveMeshUI`](https://github.com/JustAGHosT/CognitiveMeshUI)  
- DevEx / AI in delivery: [`autopr-engine`](https://github.com/JustAGHosT/autopr-engine)

**For DeFi / crypto + risk**

- Smart contracts & risk math: [`vv-chain`](https://github.com/JustAGHosT/vv-chain)  
- Services / APIs: [`vv-chain-services`](https://github.com/JustAGHosT/vv-chain-services)  
- Infra & policy: [`vv-iac`](https://github.com/JustAGHosT/vv-iac)  
- Docs & product surface: [`vv-docs`](https://github.com/JustAGHosT/vv-docs), [`vv-landing`](https://github.com/JustAGHosT/vv-landing)

**For “can this person handle messy reality?”**

- Regenerative farm partnership & ROI: [`zeeplan`](https://github.com/JustAGHosT/zeeplan)  
- Operational agri system: [`pigpro`](https://github.com/JustAGHosT/pigpro)  
- Broader farm planning: [`farm-business-plan`](https://github.com/JustAGHosT/farm-business-plan)  
- Security / hardware concept: [`PhoenixRooivalk`](https://github.com/JustAGHosT/PhoenixRooivalk)

**For generic engineering quality**

- Full‑stack template: [`crisis-unleashed-app`](https://github.com/JustAGHosT/crisis-unleashed-app)  
- Infra & homelab: [`home-lab-setup`](https://github.com/JustAGHosT/home-lab-setup)

If you only have 5–10 minutes, skim the READMEs in **cognitive-mesh, vv-chain, vv-chain-services, zeeplan, pigpro**.

---

## Tech & practices (short version)

**Cloud & infra**

- Azure, Azure DevOps  
- Terraform, Bicep, PowerShell  
- VPN, DNS, TLS automation, cost guardrails

**Stacks**

- C# / .NET, Solidity  
- Python / FastAPI  
- TypeScript / React / Next.js / Astro / Svelte

**Architecture & delivery**

- Event-driven & service-based systems  
- Policy-as-code, IaC promotion, `what-if` gates  
- OpenTelemetry, structured logging, cost/latency baselines  
- GitHub Actions CI/CD, quality gates, test harnesses  
- Hexagonal / layered architectures, domain modules

---

## Contact

- LinkedIn: [linkedin.com/in/juriesmit](https://www.linkedin.com/in/juriesmit)  
- GitHub: you’re here – feel free to open issues or PRs on any of the repos above.
