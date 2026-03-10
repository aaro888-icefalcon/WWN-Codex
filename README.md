# Emergence Exile RPG — Orientation Hub

This page is the permanent starting point for contributors. Choose your mode, then use only the canonical docs below.

## 1) Develop/Edit the game system

- [Development documentation](development/index.md)
- [Runtime content inventory](runtime/index.md)
- [Scripts registry](runtime/scripts/index.md)

## 2) Run the game

- [Play runbook](runtime/play-runbook.md)
- [Turn loop workflow](runtime/turn-loop.md)

## Mode selection

- **Development mode**: use when changing code, schemas, docs, tests, scripts, or CI behavior. Governing instructions: [root AGENTS.md](AGENTS.md).
- **Runtime mode**: use when executing game turns and runtime operations without making system changes. Governing instructions: [runtime AGENTS.md](runtime/AGENTS.md).

## Governance

- **AGENTS.md** files define behavioral and validation constraints per scope. One per directory, auto-loaded.
- **index.md** files are for navigation and content discovery.
- See `AGENTS.md` for full file conventions.
