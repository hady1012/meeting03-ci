# meeting03-ci

DevOps course, meeting 3: Build, Test and Continuous Integration.

Local checks:

    python -m compileall src tests
    python -m ruff check .
    python -m pytest -q

This project uses GitHub Actions for continuous integration.
