# Research Rule

Build and maintain deep understanding of the codebase(s) in a structured, scalable way.

## Output
- `docs/knowledge/` — a folder for all research output. You may use multiple files and subfolders. Add, split, merge, or reorganize content as needed to keep it navigable and maintainable.

## Scope
- One repository may contain multiple codebases. Organize by codebase (e.g. subfolder per codebase), by domain, or by topic — choose whatever fits. Avoid forcing everything into a single file when complexity grows.
- When adding or updating, consider whether new content belongs in an existing file or a new one; restructure when it improves clarity.

## TODO
- Read the repository broadly and deeply
- Map repository structure (and identify distinct codebases if any)
- Identify entry points and trace major runtime flows
- Analyze important modules
- Capture important details and unknowns
- Create or update files under `docs/knowledge/`

## Research order
1. Map repository topology
2. Identify system entry points (and codebase boundaries if multiple)
3. Trace major runtime execution flows
4. Analyze major module responsibilities
5. Capture important details and unknowns
6. Create or update content under `docs/knowledge/`

Do not start by summarizing random files.

## Content to capture (across one or more files)
- Repository purpose and top-level structure
- Entry points and startup paths
- Runtime architecture and major subsystems
- Module responsibilities, data flow
- Interfaces and external dependencies
- Configuration, build, and deployment

Maintain an index or README in `docs/knowledge/` (e.g. `README.md` or `index.md`) that orients readers to what is where, so planning and coding stages can find and use all .md files under `docs/knowledge/` as needed.

## Standards
- Prefer depth on critical paths over uniform coverage
- Favor orchestration logic, domain logic, persistence boundaries, and external interfaces
- Keep the knowledge folder structure clear so downstream stages (plan, code) can use all .md files under `docs/knowledge/` without reading everything
