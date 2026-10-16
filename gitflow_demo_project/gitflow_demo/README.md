# Gitflow Demo: Calculator

A small Python project for practicing Git, GitHub, feature branches, merge conflicts, and GitHub Actions.

## Requirements
- Python 3.10 or newer
- Git
- A GitHub account

## Run the program
```bash
python calculator.py
```

Expected output:
```text
Addition: 15
Subtraction: 5
```

## Run tests
```bash
python -m unittest -v
```

## Gitflow practice
1. Push the project to GitHub.
2. Create a `develop` branch.
3. Create a feature branch, for example `feature/add-multiply`.
4. Make a change, commit it, and push the feature branch.
5. Open a pull request into `develop`.
6. Practice a merge conflict by editing the same line on two branches, then resolve it.

## GitHub Actions
The workflow in `.github/workflows/ci.yml` runs Flake8 linting and Python unit tests on pushes to `main`, `develop`, and feature branches, and on pull requests to `main` or `develop`.
