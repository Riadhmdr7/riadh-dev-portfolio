# Conventions

## Workflow
- Work on a branch (`feature/short-name`), then merge into `main` through a pull request.
- Keep `main` green: CI must pass before merging.

## Commit messages
- Present tense and specific: `Add data loader for MNIST`, not `stuff` or `update`.

## Code
- Python 3.11+, formatted and linted with `ruff`.
- Every project has at least a few `pytest` tests.
- Never commit secrets: put keys in `.env` (ignored by git) and document them in `.env.example`.
