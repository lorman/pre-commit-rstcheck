pre-commit-rstcheck
===================

Mirror of rstcheck package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For rstcheck: see https://github.com/myint/rstcheck

### Using csslint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/lorman/pre-commit-rstcheck
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: rstcheck
