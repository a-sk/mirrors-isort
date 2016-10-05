isort mirror
=============

Mirror of isort package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For isort: see https://github.com/timothycrosley/isort


### Using isort with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/a-sk/mirrors-isort
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: isort
