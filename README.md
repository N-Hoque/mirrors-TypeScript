# TypeScript mirror

Mirror of TypeScript package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

### Using `tsc` with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/N-Hoque/mirrors-TypeScript
  rev: "" # Use the sha / tag you want to point at
  hooks:
    - id: tsc
```
