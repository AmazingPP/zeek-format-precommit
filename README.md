# Pre-commit Hooks for zeek-format

This repository contains configuration to add [zeek-format](https://github.com/zeek/zeekscript#zeek-format) hooks to a git project using [pre-commit](https://pre-commit.com/).

## Usage

To add `zeek-format` to your pre-commit configuration, add something like the following to your `.pre-commit-config.yaml` file:

```yaml
repos:
  - repo: https://github.com/AmazingPP/zeek-format-precommit
    rev: v1.2.0
    hooks:
    - id: zeek-format
```
