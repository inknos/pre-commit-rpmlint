pre-commit-rpmlint
==================

Basic configuration of `rpmlint` hook for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For rpmlint: see https://github.com/rpm-software-management/rpmlint


### Using rpmlint with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/inknos/pre-commit-rpmlint
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: rpmlint
```
