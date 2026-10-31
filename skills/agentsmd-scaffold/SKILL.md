---
name: agentsmd-scaffold
description: Generate a first-draft AGENTS.md skeleton for the current repo from a fixed template, leaving TODOs where repo-specific knowledge is needed.
---
# AGENTS.md scaffold

Create `AGENTS.md` at the repo root if it doesn't exist (never overwrite without asking). Fill only what you can read directly from the repo, such as package.json scripts, Makefile or README. Leave `TODO:` for everything else.

```markdown
# AGENTS.md
## Project
TODO: one-paragraph description, main stack.
## Commands
- Install: TODO
- Test: TODO
- Lint: TODO
## Conventions
- TODO: naming, folder layout, style rules.
## Boundaries
- Never: TODO (e.g. edit generated files, commit secrets).
## Done means
- Tests pass, lint clean, change summarised.
```

This produces a draft. A human who knows the repo has to resolve the TODOs.
