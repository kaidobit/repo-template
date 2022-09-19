# Overview

This repository is an overview and setup of tools I think should be mandatory for any repository. **This is meant to be copy pasted.**
It will grow from time to time.

# Tools
- [direnv](https://github.com/direnv/direnv) - executes a .envrc when enteringa directory (perfect for setup of local dev environment e.g. python/nodejs environment)
- [pyenv](https://github.com/pyenv/pyenv)/[nodeenv](https://github.com/ekalinin/nodeenv) - these are beeing bootstraped during .envrc execution and are used to install cli-tools into
- [pre-commit](https://github.com/pre-commit/pre-commit) - executes different checks on staged files right before a commit happens ([pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks), [cfn-python-lint](https://github.com/awslabs/cfn-python-lint))
