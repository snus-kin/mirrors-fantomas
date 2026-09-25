# [prek](https://github.com/j178/prek) hook for fantomas

> **Note:** this hook requires `additional_dependencies` which pre-commit does not support for dotnet — use [prek](https://github.com/j178/prek) instead.

Current version: **8.0.5**

## Usage

```yaml
  - repo: https://github.com/snus-kin/mirrors-fantomas
    rev: v8.0.5
    hooks:
      - id: fantomas
        name: Fantomas
```

## How it works

A daily GitHub Actions workflow checks NuGet for new stable Fantomas releases. When a new version is found, it commits updated hook files and a new `v{version}` tag — so pinning to a tag always gives you an exact, reproducible install.
