# DSE316 2024-25

## Description

This repo contains all implementations and code for the DSE316 course taught by Prof. Vinod Kurmi as IISER Bhopal.

## Installation

### Virtual Environment

1. Create a virtual environment
2. Activate it
3. Check if it is activated
4. Install (`poetry`)[https://poetry.org] for dependency management

```bash
$ python -m venv .venv
$ . .venv/Scripts/activate  # Windows
$ . .venv/bin/activate      # Linux
$ which python              # Check which environment is active
$ python -m pip install --upgrade pip
$ python -m pip install poetry
$ poetry --version          # Check if poetry installed properly
$ poetry install            # Installs all dependenies
```

### Usage

The folders in `src/` contain all code required to make models as discussed in class.
Import them and use in your custom models.

Run your code with poetry to avoid import errors

```bash
$ poetry run python -m <your.module.name>
```
