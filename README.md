scss-lint mirror
================

Mirror of scss-lint gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For scss-lint: see https://github.com/causes/scss-lint


### Using scss-lint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/pre-commit/mirrors-scss-lint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: scss-lint
