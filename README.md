# nbx-demo

A small uv project for trying [nbx.nvim](https://github.com/estherjk/nbx.nvim): Jupyter notebooks in
Neovim with Rex action support.

## Setup

```sh
uv sync
```

This creates `.venv` with `ipykernel`, `matplotlib` and `numpy`. nbx finds that
environment on its own and runs the notebook's kernel in it.

## Try it

```sh
nvim notebooks/tour.ipynb
```

Press Shift+Enter in a cell to run it. The tour walks through the rest.

To use another library in a notebook, add it to the project as usual
(`uv add pandas`), then restart the kernel with `\R`.
