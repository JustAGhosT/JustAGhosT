# Jurie “JustAGhosT” Smit — Agentic Platform & Governance Architect

[![Email](https://img.shields.io/badge/email-smit.jurie%40gmail.com-blue)](mailto:smit.jurie@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-juriesmit-informational)](https://www.linkedin.com/in/juriesmit)

I specialize in the entire vertically integrated stack: agent runtime → policy spine → governed Azure infra → AI PR automation → telemetry UI. Outcome: faster, safer iteration (governed, observable, low-friction).

**Platform Slice (Code > Claims)**
- cognitive-mesh: Agent / LLM orchestration + RBAC + audit + policy gate (RAG-ready seams).
- CognitiveMeshUI: Next.js surface; token-driven components; interaction + UX telemetry.
- autopr-engine: AI-in-the-loop PR analysis (semantic + heuristic weighting) to compress review latency.
- vv-iac: Azure infra as code (Bicep/Terraform) with what-if + policy chain (cost/compliance drift prevention).
- crisis-unleashed-app: React + FastAPI clean architecture bootstrap / teaching asset.
- home-lab-setup: Reproducible Azure homelab (P2S VPN, cert lifecycle, monitoring, cost guardrails).

**Active Work (Live)**
- Optimizing policy evaluation latency + deterministic audit event schema.
- Reducing autopr-engine false positives (semantic diff weighting refinement).
- Collapsing IaC promotion steps (pre-merge what-if + policy condensation).

**Skim These First**
1. cognitive-mesh /governance → policy_evaluation entrypoint
2. autopr-engine /core → review_strategy logic
3. vv-iac /pipelines → gated promotion pattern

**Representative Governance Check**
```python
decision = policy_engine.evaluate(workflow_id, context)

if not decision.allow:
    audit.log(
        workflow_id,
        blocked=True,
        policy=decision.policy_id,
        reason=decision.reason
    )
    raise GovernanceBlock(decision.reason)

trace.record(
    workflow_id,
    policy=decision.policy_id,
    eval_ms=decision.eval_ms
)
```

**Stack & Practices**
Azure • Bicep/Terraform • .NET • Python/FastAPI • TypeScript/Next.js • REST/gRPC • Event-driven • OpenTelemetry • Policy-as-Code • GitHub Actions • Selective DDD/hex

**Quick Nav**
[Agent Core](https://github.com/JustAGhosT/cognitive-mesh) • [PR Automation](https://github.com/JustAGhosT/autopr-engine) • [Infra Guardrails](https://github.com/JustAGhosT/vv-iac) • [UI Surface](https://github.com/JustAGhosT/CognitiveMeshUI)

**Contact**
Email: smit.jurie@gmail.com · LinkedIn: https://www.linkedin.com/in/juriesmit
