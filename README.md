<div align="center">

# protosphinx

[**@protosphinx**](https://x.com/protosphinx) · Singapore · San Francisco · Kanpur

*Sanskrit roots. V8 fists. Ship the whole dataset.*

</div>

---

Every layer of the stack is more legible when you build it once from scratch. The ZK prover. The garbage collector. The distributed clock. The differentiable simulator. The local AI runtime. Each one was abstracted into a black box years ago and is more interesting reopened than left shut.

Right now the public work splits into four lanes: skills that make AI agents useful to people starting from zero, on-device AI for browser apps, research crates that rebuild hard systems primitives from first principles, and civic / industrial infrastructure writing for India.

## Building now

| | |
|---|---|
| **[sphinxstack](https://github.com/protosphinx/sphinxstack)** | A stack of skills for your AI agent, made for people starting from zero. 103 skills and 149 project briefs as plain files — load one into Codex, Claude Code, Copilot, Gemini, or Cursor and do the thing: build your resume, put a website live, ship a working app. Everything is a skill, including the resume. Live at [sphinxstack.com](https://sphinxstack.com); [spawn](https://github.com/protosphinx/spawn) is the template repo that coaches you through a project. |
| **[dhamaka](https://github.com/protosphinx/dhamaka)** | Local AI capability layer for web apps. Reflex and Transform ship today: smart fields, smart forms, contextual spellcheck, smart paste, formula rewrite / explain / debug, task registry, `window.ai` / Transformers.js / WASM / mock engines, cross-site model cache, demos, CI. The thesis is simple: stop sending data to the model; ship the model to the data. |
| **[erp.ai](https://erp.ai)** | Substrate for agent-driven SaaS. ERP is the example, not the target. Dhamaka's formula work is the local-AI path for the spreadsheet-shaped parts of it. |

## Research

Four Rust crates, each one a working v0 primitive with tests passing and a roadmap that continues from the code already shipped.

| | | |
|---|---|---|
| **[shunya](https://github.com/protosphinx/shunya)** *(शून्य)* | *zero, zero-knowledge* | 64 tests · Goldilocks · NTT · sumcheck · Merkle · FRI · adversarial soundness · hand-rolled SHA-256 · → 32-byte hash |
| **[kala](https://github.com/protosphinx/kala)** *(काल)* | *time, in a Rust crate* | 81 tests · Lamport · HLC · vector · ITC · LWW · wire · causal broadcast · MCP server · → Loom |
| **[samsara](https://github.com/protosphinx/samsara)** *(संसार)* | *endless rebirth* | 54 tests · tri-color · mark-region · SATB · concurrent marker · Treiber · hazards · ABA-safe stack · → Loom |
| **[maya](https://github.com/protosphinx/maya)** *(माया)* | *the rendered world* | 42 tests · Wengert tape · Tensor · matmul · RK4 · broadcasting · rigid bodies · ReLU + contact · → 2D contact |

## Systems

- **[loduloading](https://github.com/protosphinx/loduloading)** - *the opposite of lazy loading.* Fetch everything, encode it once, keep it out of the JS heap, and walk it with zero-copy WASM handles. 2.2 KB `no_std` Rust core; 11 real-WASM roundtrip tests.
- **[jsonic](https://github.com/protosphinx/jsonic)** - *L1 blockchain that tokenizes real-world manufacturing.* Proof of Transaction, PageRank reputation, DAO side-chains, Solstice main-chain sync, sled-backed JSON-RPC node, and 61 tests across crypto, POT, PageRank, persistence, RPC, and Sybil resistance.
- **[in](https://github.com/protosphinx/in)** - *The Indic Accelerationism manifesto.* Hard infrastructure, manufacturing capacity, anti-corruption institutions, factory-time metrics, and the manufacturing policy / industrial-base math work around it.

## Also

- **[gyaan](https://github.com/protosphinx/gyaan)** - reading list. annotated, opinionated, mostly correct.
- **[yapping](https://github.com/protosphinx/yapping)** - a `/now` page. updated when something changes, not on a schedule.
- **[bloat](https://github.com/protosphinx/bloat)** - maximalist dotfiles. everything you were told not to install.

---

<div align="center">

[**@protosphinx**](https://x.com/protosphinx) · live, on the timeline

</div>
