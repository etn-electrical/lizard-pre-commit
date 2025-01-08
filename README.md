# lizard-pre-commit

`lizard` package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For lizard: see https://github.com/terryyin/lizard


### Using lizard with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/etn-electrical/lizard-pre-commit
    rev: 'v1.17.13'  # Use the sha / tag you want to point at
    hooks:
    -   id: lizard
```
