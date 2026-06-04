# autometion

This repository includes a GitHub Actions CI workflow at `.github/workflows/ci.yml`.

## CI pipeline

- Runs on push and pull request to `main` and `master`
- Tests on Python 3.10, 3.11, and 3.12
- Installs development dependencies from `requirements-dev.txt`
- Runs `pytest` and `flake8`
