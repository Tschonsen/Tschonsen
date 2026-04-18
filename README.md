# Hi, I'm Jonas Wirsching

Creative systems thinker building at the intersection of **simulation**, **AI tooling**, and **developer experience**.

I write Java and React myself; for everything else (C# .NET, Rust, Python) I work with Claude Code as a pair-programming partner. The result is one person shipping at a scope that normally takes a team — which, in 2026, is exactly the skill that matters.

---

## What I'm building

### [StockSim](https://github.com/Tschonsen/StockSim) — Realistic stock market simulator
C# .NET simulation engine + Electron/React UI. **~48 000 LOC**, **530 tests**, **18 interacting market systems** (monetary policy, supply-chain propagation, options market with full Greeks, meme-stock dynamics, a regulator that flags suspicious trading).

### [Claude Token Tracker](https://github.com/Tschonsen/claude-token-tracker) — Local Claude Code cost dashboard
Tauri + React. Parses Claude Code telemetry on disk, persists to SQLite, renders daily cost, per-model breakdown, cache-hit rate, peak-hour heatmap, monthly projection. Fully offline. 3.9 MB installer.

### CodeBrain *(in progress)* — MCP server that Claude Code uses as a sub-agent
Local inference backend (Qwen-Coder via Ollama) exposed as MCP tools. Claude Code delegates bulk work (content generation, UI polish, boilerplate) to save context window and rate-limit budget, while keeping reasoning for the hard parts. Think *Claude-offloader*, not *Claude-replacement*.

---

## Stack

- **Native:** Java (Spring) · TypeScript · React · NoSQL
- **With AI partner:** C# · .NET · Rust · Python · Electron · Tauri
- **Tooling:** Claude Code, MCP, local LLMs (Ollama / Qwen-Coder), SQLite, WebSocket, ONNX

---

## Currently

Polishing StockSim, building CodeBrain, and exploring what it really means for one developer to work effectively with an AI teammate on non-trivial systems.

**Open to hire** for roles where that combination is the whole point.

<sub>📍 Based in Germany · bilingual DE/EN · reach me via GitHub</sub>
