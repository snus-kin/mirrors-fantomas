# [prek](https://github.com/j178/prek) hook for fantomas

please note you cannot use this hook with pre-commit as it does not support dotnet additional-deps


example config:
```yaml
  - repo: https://github.com/snus-kin/mirros-fantomas
    rev: v7.0.5
    hooks:
      - id: fantomas
        name: Fantomas
```
