# ruff pre-commit hook

pre-commit hook of ruff with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For ruff: see [here](https://github.com/charliermarsh/ruff)

## Using ruff with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-ruff
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: ruff-conda
```
