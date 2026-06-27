# espn-ingest

FastAPI service for ingesting ESPN public API data into Postgres

## Development

```bash
uv sync --all-groups
uv run ruff check --fix
uv run ruff format
uv run ty check
uv run pytest
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

See [LICENSE](LICENSE).
