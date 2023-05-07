# Contributing

## Bootstrap

Use the following commands to create the initial [pyproject.toml](pyproject.toml).

```bash
poetry init
poetry config virtualenvs.in-project true --local
poetry add --group dev black flake8 jupyter mypy
```
