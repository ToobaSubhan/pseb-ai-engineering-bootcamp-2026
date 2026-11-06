# PSEB AI Engineering Bootcamp 2026

Small Python exercises for the PSEB AI Engineering Bootcamp.

## Project files

- `main.py` defines `is_adult(age)`, which returns whether an age is at least 18 and raises `ValueError` for negative ages.
- `test_main.py` contains tests for adult, underage, and negative-age inputs.
- `github_api.py` queries the GitHub user API for a short list of usernames and prints their public repository counts.
- `Library.sql` is an empty SQL file reserved for future exercises.

## Requirements

- Python 3
- `pytest` to run the tests
- `requests` to run the GitHub API exercise

Install the packages with:

```bash
python -m pip install pytest requests
```

## Run the tests

```bash
python -m pytest -q
```

## Run the GitHub API exercise

```bash
python github_api.py
```
