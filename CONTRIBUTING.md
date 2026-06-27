# Contributing to espn-ingest

Thanks for your interest in contributing.

## Setup

```bash
uv sync --all-groups
```

## Before opening a pull request

```bash
uv run ruff check --fix
uv run ruff format
uv run ty check
uv run pytest
```

## Pull requests

Keep changes focused, include tests when needed, and update documentation when behavior changes.

By contributing, you agree that your contributions are licensed under this repository's license.
