# Titanic Data Cleaning Project

This project explores the Titanic dataset and performs a simple data cleaning workflow.

## Project structure

- `archives/` - dataset files used in the analysis
- `notebooks/` - Jupyter notebook with the data cleaning steps
- `main.py` - simple entry point for the project
- `pyproject.toml` - Python project configuration and dependencies

## Requirements

- Python 3.13+
- `uv` (recommended) or `pip`

## Installation

Using `uv`:

```bash
uv sync
```

Using `pip`:

```bash
python -m venv .venv
source .venv/bin/activate
pip install .
```

## Running the project

Run the main script:

```bash
python main.py
```

Open the notebook:

```bash
jupyter notebook notebooks/analise.ipynb
```

## Dataset

The project uses the Titanic dataset stored in the `archives/` folder.

## Goal

The goal is to clean and prepare the dataset for further analysis or machine learning tasks.
