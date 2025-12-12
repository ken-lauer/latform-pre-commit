# latform-pre-commit

Pre-commit hook for latform, a Bmad lattice parser/formatter tool.

### Using latform with pre-commit

To run latform's formatter via pre-commit, add the following to your `.pre-commit-config.yaml`:

```yaml
repos:
  - repo: https://github.com/ken-lauer/latform-pre-commit
    rev: v0.1.1
    hooks:
      - id: latform-format
```
