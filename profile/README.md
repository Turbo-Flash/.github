<p align="center">
  <img src="https://avatars.githubusercontent.com/u/350388441?s=200&v=4" width="112" height="112" alt="Turbo Flash" />
</p>

<h1 align="center">Turbo Flash</h1>

<p align="center">
  <strong>Local-first AI coding IDE</strong><br />
  Small footprint. Fast workflow. Your code stays yours.
</p>

<p align="center">
  <code>Desktop</code>
  &nbsp;·&nbsp;
  <code>Agent</code>
  &nbsp;·&nbsp;
  <code>CLI</code>
  &nbsp;·&nbsp;
  <code>Privacy-first</code>
</p>

---

## What it offers

Turbo Flash is an independent AI coding stack you run yourself — not a thin client for someone else’s cloud.

| Surface | What you get |
| --- | --- |
| **Desktop IDE** | Native Tauri + React + Monaco shell: explorer, tabs, agent chat, staged diffs, tests, activity log |
| **Agent runtime** | Owns the agent loop, tools, providers, and privacy gates — not an OpenCode wrapper |
| **CLI** | Interactive `turbo-flash` sessions over the same engine |

### Defaults that protect your repo

- **Local Ollama first** — inference on your machine
- **Staged edits** — accept or reject before anything hits disk
- **Explicit cloud approval** — OpenRouter / remote models only after a task-scoped yes
- **No silent fallbacks** that ship source off-machine

## Why it exists

Most “AI IDEs” are UI around a remote model. Turbo Flash inverts that: one engine, local by default, desktop and CLI as equal citizens.

```bash
turbo-flash model
turbo-flash open .
turbo-flash ask "fix the failing tests"
```

## Repositories

| Repo | Role |
| --- | --- |
| `turbo-flash-desktop` | Native IDE |
| `turbo-flash-agent` | Agent runtime + provider gateway |
| `Turbo-Flash-CLI` | Terminal front-end |
| `turbo-flash-website` | Product site |

> Product repositories are private while the MVP hardens. This profile is the public face of the stack.

---

<p align="center">
  <sub>Built in Egypt · Independent · Privacy-first</sub>
</p>
