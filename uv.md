# uv

## Init

```sh
uv init
```

## Create virtual environment

```sh
uv sync
```

## Run

```sh
uv run src/main.py
# モジュールとして実行する場合
uv run python -m src.main
```

## Install package

### Install from PyPI

```sh
uv add requests
```

### Install only dependencies

```sh
uv add --dev types-requests
```

### Update package

```sh
uv add --upgrade requests
uv add --upgrade --dev types-requests
```
