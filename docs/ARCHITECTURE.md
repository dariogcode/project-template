# Architecture

> One page, not a treatise. If this grows too large, split it into documents per subsystem.

## Overview

<!-- Paragraph describing the system at a high level. What components exist, how they communicate. -->

## Diagram

```
[Client] → [API] → [Service] → [DB]
                      ↓
                  [Queue/Worker]
```

<!-- ASCII art, Mermaid, or a link to an image. Don't over-design. -->

## Components

### <Component 1>

- **Responsibility:**
- **Code location:**
- **Dependencies:**
- **Notes:**

### <Component 2>

- **Responsibility:**
- **Code location:**
- **Dependencies:**
- **Notes:**

## Main flows

### Flow: <name of critical flow>

1. Step 1
2. Step 2
3. Step 3

## System boundaries

<!-- What this system does NOT do. What it takes as given. -->

-

## Key decisions

Decisions that shaped this architecture are recorded in [`decisions/`](decisions/). The most relevant ones:

- [ADR-001: ...](decisions/001-...md)

## Known technical debt

<!-- Things we know should be improved but aren't a priority right now. -->

-
