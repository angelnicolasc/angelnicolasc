# Hey, I'm Nick 👋

🤖 **AI agent infrastructure builder** · 🎓 **B.S. CS · MBA Candidate** · 🚀 **Founder @DrakoLabs**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![CLI](https://img.shields.io/badge/-CLI-000000?style=flat-square&logo=gnu-bash&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)

> Obsessed with the unglamorous substrate that separates autonomous deployments from demos. Building the answer

---

## Projects

- 🐉 **[Drako](https://github.com/DrakoLabs/drako)** — the security layer your AI agents are missing. Scans your codebase before you ship, enforces policy at runtime, and blocks bad tool calls before they execute. 97 deterministic rules, zero LLMs in the eval loop, <2ms overhead.


- 🧠 **[Graymatter](https://github.com/angelnicolasc/graymatter)** — persistent memory layer for AI agents. Turns stateless agents into stateful ones with a single Go binary. Hybrid retrieval (vector + keyword + recency), ~90% token reduction after a few sessions. Zero infra, zero dependencies—a true drop-in solution. Auto-wires with any vendor (Claude Code, Cursor, Codex, OpenCode, Antigravity) and any MCP-compatible client.

- 🌐 **[Stratum](https://github.com/angelnicolasc/stratum)** — dual-tier LLM inference router for Gemma 4 on 16GB consumer GPUs. Zero-inference complexity scorer (6 dimensions, precompiled regexes) decides in <1ms whether a request goes to vLLM for speed or llama.cpp for quality, backed by live VRAM monitoring and adaptive latency SLA enforcement via EMA. Full model quality at fraction of the hardware cost.

---

## What I'm Building Toward

- **Self-evolving harnesses** — FSM-driven mutation loops with snapshot-
  backed rollback; systems that get better between runs, not between
  deploys
- **Agentic governance** — policy-as-code that travels with the agent,
  enforced at the execution layer before the damage is done
- **Formal verification for autonomous systems** — if you can't prove
  what your agent won't do, you don't control it
- **High-performance enforcement** — sub-millisecond policy evaluation
  on hot paths; governance that doesn't make your agents slow
