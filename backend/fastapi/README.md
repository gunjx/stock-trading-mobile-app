# FastAPI Server

## Prerequisites

- Python 3.11.2 (e.g. by using pyenv)
- Poetry

## Install dependencies

```bash
poetry env use 3.11.2
poetry install
```

## Run server

Run the service locally:

```bash
poetry shell
uvicorn app.main:app --reload
```
