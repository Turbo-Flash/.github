<p align="center">
  <img src="https://avatars.githubusercontent.com/u/350388441?s=200&v=4" width="112" height="112" alt="Turbo Flash" />
</p>

<h1 align="center">Turbo Flash</h1>

<p align="center">
  <strong>Local-first AI coding IDE</strong><br />
  Small footprint. Fast workflow. Your code stays yours.
</p>

<p align="center">
  <a href="https://github.com/Turbo-Flash/turbo-flash-desktop/releases/latest">Download</a>
  ·
  <a href="https://github.com/Turbo-Flash/turbo-flash-desktop">Desktop</a>
  ·
  <a href="https://github.com/Turbo-Flash/turbo-flash-agent">Agent</a>
  ·
  <a href="https://github.com/Turbo-Flash/Turbo-Flash-CLI">CLI</a>
</p>

---

## What it is

Turbo Flash is an independent AI coding stack you run yourself:

| Surface | Role |
| --- | --- |
| **Desktop** | Tauri + React + Monaco IDE — explorer, tabs, agent chat, diff review, tests |
| **Agent** | Owns the agent loop, tools, providers, and privacy gates — not an OpenCode wrapper |
| **CLI** | Interactive terminal front-end over the same engine |

Local **Ollama** is the default. Cloud providers (e.g. OpenRouter) only run after **explicit, task-scoped approval**. No silent fallbacks that ship your repo off-machine.

## Why it exists

Most “AI IDEs” are thin clients for someone else’s cloud. Turbo Flash is built the other way around:

- **Local by default** — inference on your machine when you want it
- **Staged edits** — read the diff, accept or reject before anything hits disk
- **Explicit permissions** — tests and cloud calls ask first
- **One engine** — desktop and CLI share `turbo-flash-agent`

## Start here

```bash
# Desktop (macOS Apple Silicon / Linux)
# → https://github.com/Turbo-Flash/turbo-flash-desktop/releases/latest

# Or drive the engine from the terminal
turbo-flash model
turbo-flash open .
turbo-flash ask "fix the failing tests"
```

## Repositories

| Repo | What you get |
| --- | --- |
| [`turbo-flash-desktop`](https://github.com/Turbo-Flash/turbo-flash-desktop) | Native desktop IDE shell |
| [`turbo-flash-agent`](https://github.com/Turbo-Flash/turbo-flash-agent) | Agent runtime + provider gateway |
| [`Turbo-Flash-CLI`](https://github.com/Turbo-Flash/Turbo-Flash-CLI) | Interactive CLI (`turbo-flash`) |
| [`turbo-flash-website`](https://github.com/Turbo-Flash/turbo-flash-website) | Product site |

---

<p align="center">
  <sub>Built in Egypt · Independent · Privacy-first</sub>
</p>
