# Hey, I'm Nick 👋

🤖 **AI Infrastructure Engineer** · 🎓 **B.S. CS · MBA Candidate** 

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![CLI](https://img.shields.io/badge/-CLI-000000?style=flat-square&logo=gnu-bash&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)

> Obsessed with the unglamorous substrate that separates autonomous deployments from demos.

---

## Projects

- 🐉 **[Drako](https://github.com/DrakoLabs/drako)** — the security layer your AI agents are missing. Scans your codebase before you ship, enforces policy at runtime, and blocks bad tool calls before they execute. 97 deterministic rules, zero LLMs in the eval loop, <2ms overhead.


- 🧠 **[Graymatter](https://github.com/angelnicolasc/graymatter)** — persistent memory layer for AI agents. Turns stateless agents into stateful ones with a single Go binary. Hybrid retrieval (vector + keyword + recency), ~90% token reduction after a few sessions. Zero infra, zero dependencies—a true drop-in solution. Auto-wires with any vendor (Claude Code, Cursor, Codex, OpenCode, Antigravity) and any MCP-compatible client.

- ⚡ **[Forge](https://github.com/angelnicolasc/forge)** — Universal multi-agent harness. Adapts LangGraph, CrewAI, AutoGen (zero migration, auto-detected) with per-agent cost tracking, hybrid memory retrieval, observability, and self-evolution. 11 composable packages, zero framework lock-in.

- 🌐 **[Stratum](https://github.com/angelnicolasc/stratum)** — dual-tier LLM inference router for Gemma 4 on 16GB consumer GPUs. Zero-inference complexity scorer (6 dimensions, precompiled regexes) decides in <1ms whether a request goes to vLLM for speed or llama.cpp for quality, backed by live VRAM monitoring and adaptive latency SLA enforcement via EMA. Full model quality at fraction of the hardware cost.

- 🔬 **[Epica](https://github.com/angelnicolasc/epica)** — formal belief revision runtime for LLM agents, grounded in AGM postulates. Where other memory systems store contradictions silently, Epica resolves them: minimal contraction removes what must go, Noisy-OR propagates confidence causally, C=(P,I,G,R) contracts enforce policy before the agent acts. K*2-K*5 verified. T-ECE 0.07 < 0.08. MCP 2026 native. PyO3 SDK.

- 🧭 **[Meridian](https://github.com/angelnicolasc/meridian)** — phase-aware inference scheduler for reasoning models, grounded in recent EAT/RPDI research on reasoning termination. Reframes a single request as two workloads with opposite SLOs, then schedules them accordingly: output-first dual-queue dispatch, EAT/RPDI-gated </ think> forcing, three-tier KV eviction, and transport-agnostic disaggregated KV offload hooks. Rust core, PyO3-backed Python/vLLM integration, and a stock-vs-Meridian A/B harness centered on TTOT, output ITL, and user-visible degradation events.
  
---

## What I'm Building Toward

- **Long-horizon drift as a typed invariant problem** — coherence is not 
  correctness; agents drift silently over 100-step trajectories while 
  sounding confident. I'm building CLT-based drift bounds enforced at the 
  belief mutation layer, not as output-level checks that arrive too late.

- **Causal failure attribution as infrastructure** — in multi-agent systems, 
  every downstream confidence collapse has an upstream cause. I treat causal 
  provenance as a first-class primitive: every belief revision needs a diff, 
  every failure needs an attributable path back to the state that originated it.

- **Formally bounded autonomy over formally verified outputs** — proving what 
  an agent won't do matters more than guardrailing what it says. AGM revision 
  semantics and typed behavioral contracts at the execution layer; enforcement 
  that disappears into the runtime at sub-millisecond latency or it becomes 
  a feature flag.
