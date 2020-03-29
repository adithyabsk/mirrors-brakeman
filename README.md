brakeman mirror
===============

Mirror of brakeman gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For brakeman: see https://github.com/presidentbeef/brakeman


### Using brakeman with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/adithyabsk/mirrors-rails-best-practices
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: brakeman


**Based on**: https://github.com/pre-commit/mirrors-ruby-lint