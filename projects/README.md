# Projects

One folder per project, numbered in the order they were built: `01-name`, `02-name`, ...

Every project should have:

- `README.md` with the problem, a demo (screenshot or GIF), how to run it, and what I learned
- `src/` for the code and `tests/` for pytest tests
- `requirements.txt` listing its dependencies
- `pyproject.toml` (copied from the template) so CI can run its tests

CI runs `ruff` and `pytest` for every folder here automatically.
