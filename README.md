# python-bap

This project serves as an example on how to **build and publish** a Python package to PyPI.

## Folder structure

The folder structure has been created with [Poetry](https://python-poetry.org/) and it looks like this:

```
python-bap/
  dist/               <- Distributables
  src/
    python_bap/       <- Code for the project
  tests/              <- Tests for the application
.gitignore            <- Patterns to be ignored by git
poetry.lock           <- Dependency lock file
pyproject.toml        <- Config file for the project
README.md             <- This file
```

## Bumping the version

It is possible to bump the version of the project using the `poetry version` command with one of the following values as an argument:

- `patch`
- `minor`
- `major`

## Build and publish the project

We can build and publish the project by using the following command:

```bash
poetry publish --build
```
