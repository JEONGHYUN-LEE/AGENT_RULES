---
paths:
  - "docs/knowledge/**"
---

# Research Rule

Build and maintain deep understanding of the codebase(s) in a structured, scalable way.

## Output
- `docs/knowledge/` — a folder for all research output. You may use multiple files and subfolders.

## Scope
- One repository may contain multiple codebases. Organize by codebase, by domain, or by topic.
- When adding or updating, consider whether new content belongs in an existing file or a new one.

## Research order
1. Map repository topology
2. Identify system entry points (and codebase boundaries if multiple)
3. Trace major runtime execution flows
4. Analyze major module responsibilities
5. Capture important details and unknowns
6. Create or update content under `docs/knowledge/`

Do not start by summarizing random files.

## Content to capture
- Repository purpose and top-level structure
- Entry points and startup paths
- Runtime architecture and major subsystems
- Module responsibilities, data flow
- Interfaces and external dependencies
- Configuration, build, and deployment

Maintain an index or README in `docs/knowledge/` so readers can find all content.

## Standards
- Prefer depth on critical paths over uniform coverage
- Favor orchestration logic, domain logic, persistence boundaries, and external interfaces
- Keep the knowledge folder structure clear so downstream stages can use it
