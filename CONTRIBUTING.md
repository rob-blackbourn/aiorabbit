# Contributing

To get setup in the environment and run the tests, take the following steps:

```bash
python3 -m venv env
source env/bin/activate
pip install -e '.[test]'

flake8
coverage run && coverage report
```

## Test Coverage

Pull requests that make changes or additions that are not covered by tests
will likely be closed without review.

In addition, all tests must pass the tests **AND** flake8 linter. If flake8
exceptions are included, the reasoning for adding the exception must be included
in the pull request.
