# example-monorepo

## Development

Create a venv with all dependencies:

```
uv sync --all-packages
```

Run pytest for a specific directory
```
uv run --directory packages/example-logging pytest
```