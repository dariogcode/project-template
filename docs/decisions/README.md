# Architecture Decision Records (ADRs)

This folder contains the important architectural decisions of the project. Each decision lives in a numbered file.

## When to write an ADR

Write an ADR when:

- The decision took thought (you evaluated several options).
- The decision will be questioned in the future ("why did we use X and not Y?").
- The decision has long-term consequences (architecture, stack, API contracts).
- The decision is counterintuitive or depends on context that isn't obvious.

Do not write an ADR for trivial decisions ("use camelCase") — those go in `CLAUDE.md` or the linter.

## How to write an ADR

1. Copy `000-template.md` to a new file with the next available number.
2. Descriptive name in kebab-case: `007-choose-pgvector-over-pinecone.md`.
3. Fill in the sections. Be concise — a long ADR doesn't get read.
4. If the decision is reversed later, don't delete the ADR: mark it as `status: superseded by ADR-XXX` and write the new one.

## Index

<!-- Update when ADRs are added -->

- [000 — Template](000-template.md)

## Format

The format is based on [Michael Nygard's](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions), which is the de facto industry standard.
