# Material for Sommerakademie Oxford

## Installation

```sh
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
```

## Build

```sh
jupyter-book clean sommerakademie-oxford/
jupyter-book build sommerakademie-oxford/
```

A fully-rendered HTML version of the book will be built in `sommerakademie-oxford/_build/html/`.

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
