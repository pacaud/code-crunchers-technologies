# POINTERS — pacaud/code-crunchers-technologies

This file is a *single-source pointer map* so an assistant can open repo files reliably via Raw URLs.

## Repo
- repo: pacaud/code-crunchers-technologies
- default_branch: main

## Raw base (DRY)
RAW_BASE:
- https://raw.githubusercontent.com/pacaud/code-crunchers-technologies/main/

## How to build any raw link
- raw_url = RAW_BASE + <path>

Example:
- RAW_BASE + "README.md"
- => https://raw.githubusercontent.com/pacaud/code-crunchers-technologies/main/README.md

## Key entrypoints (paths)
### Docs / policy
- readme: README.md
- contributing: CONTRIBUTING.md
- security: SECURITY.md
- license: LICENSE

### Dev / config (safe public)
- env_example: .env.example
- gitignore: .gitignore

## Assistant workflow notes
- If Kevin says “open CCT readme”, open: RAW_BASE + "README.md"
- If a file isn’t listed here, ask for its repo-relative path (then open RAW_BASE + that path).
