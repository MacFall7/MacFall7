# Mac McFall — M87 Studio

**AI execution governance architect.** Enforcement layers, audit trails, and authority separation for production agent systems.

I build the things that keep autonomous systems from doing irreversible damage. Most agent stacks treat governance as an afterthought; mine treats it as the substrate.

**Start here:** [Spine Lite](https://github.com/MacFall7/spine-lite-python) (governance kernel) → [Governed Swarm](https://github.com/MacFall7/m87-governed-swarm) (full reference architecture) → [StemForge](https://github.com/MacFall7/Stem-Forge) (applied system, benchmarked) → [Resonance](https://resonance.m87studio.net) (live product).

---

## What I'm building

**[M87 Studio](https://m87studio.net)** — a governance-first execution stack for AI agents. Production-grade enforcement, not best-effort suggestion.

| Layer | Project | Status |
|---|---|---|
| Governance kernel | [Spine Lite](https://github.com/MacFall7/spine-lite-python) (Python · [JVM](https://github.com/MacFall7/spine-lite-jvm) · [.NET](https://github.com/MacFall7/spine-lite.NET)) | MIT, multi-runtime |
| Reference impl | [Governance Sandbox](https://github.com/MacFall7/m87-governance-sandbox) | BSL 1.1 |
| Executable spec (BPMN) | [m87-governed-loop](https://github.com/MacFall7/m87-governed-loop) | MIT, Python + Java, CI-green |
| Agentic substrate | [Governed Swarm](https://github.com/MacFall7/m87-governed-swarm) | BSL 1.1 |
| Audit | [m87-audit-agent](https://github.com/MacFall7/m87-audit-agent) | MIT |
| Bridge | [m87-governed-bridge](https://github.com/MacFall7/m87-governed-bridge) | Claude ↔ Gemini, governed |
| Applied system | [StemForge](https://github.com/MacFall7/Stem-Forge) | MIT, local GPU audio workstation, benchmarked |
| Live product | [Resonance](https://resonance.m87studio.net) | Production |

---

## Operating thesis

1. **Proposal ≠ Execution.** Agents propose actions. Governance executes them.
2. **Authority separation.** Decision logic and execution logic stay on different sides of a contract.
3. **Fail-closed by default.** Ambiguity halts. No silent recovery.
4. **Artifact-backed completion.** No work is "done" without verifiable receipts.
5. **Model interchangeability.** No design depends on a single model.

These are the invariants the Spine Lite kernel enforces. Everything else is implementation detail.

---

## Open to

- **Advisory** — governance architecture for AI-native teams shipping autonomous systems.
- **Design partners** — for Spine Pro (regulated industries: HIPAA, OSHA, EU AI Act).
- **Conversations** — about reasoning loops, distributed execution, and where governance needs to sit in agent stacks.

---

📍 Portland, OR · 🌐 [m87studio.net](https://m87studio.net) · 💼 [LinkedIn](https://www.linkedin.com/in/macmcfall)
