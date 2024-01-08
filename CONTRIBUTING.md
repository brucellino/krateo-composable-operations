# Contributing

This file describes how this project accepts contributions and what the expectations are.

## Pre commit hooks

We use the ["pre-commit" framework](https://pre-commit.com) to manage commit hooks.
See [`.pre-commit-config.yaml`](.pre-commit-config.yaml) for which hooks are implemented specifically.

Please add these hooks to your clone of the repo by running

``` bash
pip install pre-commit
pre-commit install
pre-commit install --hook-type commit-msg
```

This should be done _before_ making any commits.


## Commit messages

This project follows the [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/#specification) message standard, which is enforced by pre-commit hooks (see above).
