# CLAUDE.md

This file provides persistent context for AI agents (Claude Code, Cursor, etc.) working on this repository. Read it in full at the start of every session.

---

## Part A — Global conventions (do not modify without reason)

### Engineering philosophy

- **Simplicity first.** Prefer serverless, lightweight solutions with few dependencies over complex infrastructure.
- **Pushback expected.** If a suggestion adds unnecessary complexity (new database, persistent service, heavy dependency), challenge it before implementing. Propose simpler alternatives.
- **YAGNI applied.** Do not build abstractions "just in case". Solve the concrete problem first.
- **Explicit over implicit.** Clear code over clever code.

### Code style

- Strict typing whenever the language allows (TypeScript strict, Python type hints, etc.).
- Descriptive names. Functions and variables should read like prose.
- Comments explain *why*, not *what*. The code already says what it does.
- Short functions, one responsibility per function.
- Tests for business logic, not for trivial getters/setters.

### Dependencies

- Do not add new dependencies without explicit consultation.
- Prefer libraries with few sub-dependencies, actively maintained, and with a stable API.
- If it can be solved with the standard library or a short piece of custom code, do it that way.

### Documentation

- Every significant change must check whether it updates: `README.md`, `ARCHITECTURE.md`, `CLAUDE.md`, or warrants a new ADR in `docs/decisions/`.
- **At the end of every task**, before saying "done", the agent must explicitly respond: "Documentation reviewed: [files updated] / [no changes required because X]".
- ADRs are written for decisions that took thought, even if tentative (mark `status: tentative`).

### Communication with the agent

- If there is not enough context for a decision, ask before assuming.
- If a user instruction contradicts what is written in this file, mention it before executing.
- When starting a new session, summarize in 3 lines what you understood about the current state of the project from the docs.

---

## Part B — Project-specific

> Fill in this section when starting the project. Everything above stays the same across projects.

### What this project is

<!-- 2-3 sentences. What it solves, for whom. -->

### Stack

- **Language:**
- **Framework:**
- **Database:**
- **Infrastructure:**
- **Testing:**

### Useful commands

```bash
# Install
# Run in dev
# Run tests
# Lint
# Build
# Deploy
```

### Project structure

<!-- Folder tree with one line per folder explaining what it contains -->

### Key architectural decisions

<!-- Links to the most important ADRs -->

- [ADR-001: ...](docs/decisions/001-...md)

### What NOT to do in this project

<!-- Project-specific restrictions. Example: "do not use ORMs", "do not add endpoints without auth", etc. -->

-

### Current state

<!-- Update regularly. What is done, what is being built, what is next. Link to TODO.md or ROADMAP.md -->

See [TODO.md](TODO.md) for details.
