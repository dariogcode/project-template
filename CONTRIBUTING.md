# Contributing

## Before you start

1. Read [`CLAUDE.md`](CLAUDE.md) — project conventions.
2. Read [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md) — how the system is structured.
3. Look at the ADRs in [`docs/decisions/`](docs/decisions/) relevant to what you're going to touch.

## Workflow

1. Create a branch off `main`: `feat/short-description` or `fix/short-description`.
2. Make the changes, with small and descriptive commits.
3. Update the affected documentation (see checklist in the PR template).
4. Open a PR. The template will guide you.

## When to write an ADR

If your change involves an architectural decision (choosing a library, a pattern, an integration), write an ADR before or alongside the code. See [`docs/decisions/README.md`](docs/decisions/README.md).

## Adding dependencies

Do not add new dependencies without justification. In the PR, explain:

- What problem it solves.
- What alternatives you considered (including "writing it by hand").
- Maintenance status of the library.

## Commit style

Suggested format (not mandatory, but helps):

```
<type>: <short description in imperative>

<optional body explaining the why>
```

Types: `feat`, `fix`, `refactor`, `docs`, `test`, `chore`.

Example:

```
feat: add /health endpoint for k8s checks

Kubernetes needs a liveness probe. Simple endpoint that returns 200
and checks the DB connection.
```
