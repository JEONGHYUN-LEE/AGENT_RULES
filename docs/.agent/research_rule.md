# Research Rule

Build deep understanding of the entire codebase and maintain it in a single long-form file.

## Output
- `docs/research.md`

## TODO
- read the repository broadly and deeply
- map repository structure
- identify entry points
- trace major runtime flows
- analyze important modules
- update `docs/research.md`

## Research order
Follow this order:

1. Map repository topology
2. Identify system entry points
3. Trace major runtime execution flows
4. Analyze major module responsibilities
5. Capture important details and unknowns
6. Update `docs/research.md`

Do not start by summarizing random files.

## `docs/research.md` should contain

1. Repository purpose
2. Top-level structure
3. Entry points and startup paths
4. Runtime architecture
5. Major subsystems and module responsibilities
6. Data flow
7. Interfaces and external dependencies
8. Configuration, build, and deployment

## Research standards
- prefer depth on critical paths over uniform coverage
- favor orchestration logic, domain logic, persistence boundaries, and external interfaces
