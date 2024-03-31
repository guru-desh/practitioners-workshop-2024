# L@S Practitioners' Workshop

Welcome to the L@S Practitioners' Workshop GitHub Repo. This repository holds the source code to build the website used to distribute information about this workshop.
We use [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) to build this webpage. We also use [poetry](https://python-poetry.org/) for dependency management.

## Getting Started

To develop locally, there's a couple of steps:

1. Install `poetry` in your python environment via `pip install poetry`
2. Run `poetry install` to create a virtual environment and install all dependencies
3. Use `poe` to develop locally

The defined actions related to the website are:

- `poetry run poe serve`: Builds the website and serves it locally (so you can see your changes)

## Deploying Website to GitHub Pages

After you have tested your changes locally, deployment to GitHub Pages is handled by GitHub Actions. After you commit your code, GitHub Actions will start building the website and deploy it automatically.
