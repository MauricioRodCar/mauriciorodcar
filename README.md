## Hi, I'm Mauricio 👋

Full-stack engineer from Mérida, Mexico (UTC-6). For 7 years I've built React/TypeScript and Node.js products for US and European clients, including Intel, Nestlé, Novo Nordisk and the Mozilla Foundation. These days I also ship AI-powered desktop apps on the Claude API, the Claude Agent SDK and local models.

**Open to remote contract work** · [Portfolio](https://www.mauriciorodriguez.dev/en) · [LinkedIn](https://www.linkedin.com/in/mauricio-rodriguez-carballo) · [Email](mailto:contact.mauricio.rodriguez@gmail.com)

---

### What I'm building

**[Levelset](https://github.com/MauricioRodCar/Levelset)**: a desktop trading-analysis cockpit · [▶ Try the web demo](https://mauriciorodcar.github.io/Levelset/)<br>
Every trade idea ends in one clear ticket (entry, stop loss, take profit), and you can inspect every step of the pipeline behind it. The app never places an order.
- Tauri 2 shell · React 18 + TypeScript UI · Python FastAPI engine on SQLite · typed client generated from an OpenAPI contract · live updates over SSE
- Optional AI assistant on the Claude API, with monthly cost caps and keys stored in the OS credential vault
- 250+ automated tests (pytest, Vitest, cargo) · GitHub Actions CI, releases and Pages demo · English/Spanish

**Wispkin**: a Windows AI desktop assistant *(public beta · source is private)*<br>
An AI assistant with an animated avatar that reacts to what the agent is doing. It runs on Claude through the Claude Agent SDK or on local Ollama models.
- Electron + TypeScript · 381 unit tests · 12 architecture decision records · built with Claude Code orchestrating 8 specialized subagents
- More on [my portfolio](https://www.mauriciorodriguez.dev/en)

**Local-first AI agent**: a sandboxed tool-calling agent on Ollama. The model only *requests* tool calls; the orchestrator validates and executes them.

---

### Stack

- **Daily:** TypeScript · React · Next.js · Node.js · Express / NestJS · PostgreSQL
- **Also:** Python (FastAPI) · PHP / WordPress · Stripe · Google Cloud · AWS · GitHub Actions · Electron · Tauri
- **AI:** Claude API · Claude Agent SDK · Ollama · tool calling · LLM output evaluation
- **Testing:** Jest · Vitest · React Testing Library · pytest

---

### Highlights from client work
- Cut page load time by 83% (12 s → 2 s) on a media site that had to survive 50x traffic spikes
- Built a Stripe subscription flow and migrated an existing subscriber base onto it without double-charging anyone
- Raised test coverage to 86% on a healthcare supply-chain app

<sub>Most of my professional code lives in private client repositories.</sub>
