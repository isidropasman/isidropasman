<p align="center">
  <img src="./assets/hero.svg?v=20260905-4" width="100%" alt="Founder · Buenos Aires · Voice AI · Agents · Learning" />
</p>

<p align="center">
  Founder · Software Engineer · Buenos Aires, Argentina
</p>

---

## Selected Work

### Plexo
AI agents for real-world workflows — turning messy human conversations into evidence-backed operational context.

→ [Engineering deep dive](https://github.com/isidropasman/plexo-engineering)

`Voice AI` · `Context Systems` · `Evals` · `Agent Systems`

### Gauntlet
A black-box proving ground for AI agents. Adversarial scenarios, tool-use simulation, reproducible evals, `pass^k`, and evidence you can actually debug.

→ [View repository](https://github.com/isidropasman/agent-evals)

`Agent Evals` · `Adversarial Testing` · `Tool Calling` · `Reliability`

### FounderOS
An evidence-driven decision system for founders: bounded context, versioned procedures, verified sources, independent challenge, replayable traces, and ablation-based evaluation.

→ [View repository](https://github.com/isidropasman/founder-os)

`TypeScript` · `Context Engineering` · `Retrieval` · `Evals` · `Provenance`

### AI Privacy Guard
Local-first privacy enforcement at the boundary between humans and AI. Detects sensitive information before it leaves the browser.

→ [View repository](https://github.com/Zent-Agency/ai-privacy-guard)

`Privacy` · `Browser Security` · `Local-first` · `LLMs`

### MacTools
I kept paying for tiny Mac utilities, so I started building my own. One native macOS app for the small tools I use every day.

→ [View repository](https://github.com/isidropasman/MacTools)

`Swift` · `SwiftUI` · `macOS` · `Developer Tools`

---

## How I build

I treat my development environment as a system. It changes constantly: I test new models, coding agents and workflows, keep what compounds, and remove what doesn't.

> **I don't optimize for writing code faster. I optimize for shortening the loop between idea, implementation, failure and learning.**

| Layer | Current setup |
|---|---|
| Editor | `Cursor` |
| Coding agents | `Claude Code` · `Codex` |
| Models | Continuously testing new models and routing work by task |
| Knowledge | `Obsidian` · architecture docs · ADRs |
| Agent context | `AGENTS.md` · `CLAUDE.md` · scoped context · reusable skills |
| Planning | Brainstorm → Spec → Plan → Execute |
| Development | TDD · small diffs · isolated worktrees when useful |
| Evaluation | Unit · integration · E2E · agent evals |
| Browser testing | `Playwright` |
| Review | `Greptile` · adversarial AI review · human review |
| Verification | Typecheck → tests → evals → E2E → diff review → ship |
| Learning loop | Production failure → root cause → test/eval → architecture/context update |

**No model loyalty.** I continuously test new models and route work to whichever one performs best for the task.

### Vanilla

**Vanilla** is the name I use for my opinionated, constantly evolving setup for building software with AI agents.

```text
                         ┌──────────────┐
                         │   OBSIDIAN   │
                         │ knowledge +  │
                         │ decisions    │
                         └──────┬───────┘
                                ↓
IDEA → SPEC → PLAN → AGENT → CODE → VERIFY → REVIEW → SHIP
                 ↑                 │                 │
                 │                 ↓                 ↓
              CONTEXT            EVALS            TRACES
                 ↑                 │                 │
                 └─────────────────┴─────────────────┘
                              LEARN
```

The tools will change. The system shouldn't depend on any one of them.

---

## Interests

`Founder` · `Voice AI` · `Agents` · `Learning` · `Evals` · `Context` · `Automation` · `Developer tools`

## Core stack

`TypeScript` · `Python` · `Node.js` · `PostgreSQL` · `Docker`

`Tool Calling` · `RAG` · `Voice AI` · `LLM Evals` · `Agent Systems`
