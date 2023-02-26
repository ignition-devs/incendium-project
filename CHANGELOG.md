## v2023.2.0 (2023-02-25)

### Feat

- **vision**: add authentication and authorization (#17)

## v2023.1.0 (2023-01-09)

### BREAKING CHANGE

- stop checking instance of `in_params` and `out_params`
- `DisposableConnection`'s `db` field has been renamed to
`database` to conform with snake_case naming style and to match the name
used in some `system.db` functions.

### Feat

- release 1.0.7
- **pre-commit**: update black 21.5b0 -> 21.5b1
- **pre-commit**: update flake8 3.9.1 -> 3.9.2
- **pre-commit**: update black 21.4b2 -> 21.5b0
- **pre-commit**: update black 21.4b1 -> 21.4b2
- **pre-commit**: update black 21.4b0 -> 21.4b1
- **pre-commit**: update black 20.8b1 -> 21.4b0
- **pre-commit**: bump flake8 to 3.9.1
- :sparkles: add function to convert Dataset into JSON
- add flake8 pre-commit hook

### Fix

- **db**: check instance of `out_params`
- bug in incendium.vision.gui constants
- break loop after expected conditions have been met

### Refactor

- use super() in base classes (#2)
- **db**: return BasicDataset on _execute_sp result_set (#81)
- fix `perflint` `W8202`
- reduce cognitive complexity
- fix SonarLint and Sourcery issues
- add pylint
- conform to snake_case naming style
- modify imports
- :zap: Simplify squence comparison as suggested by Sourcery
