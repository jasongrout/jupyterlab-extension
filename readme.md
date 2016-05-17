# Pre-alpha Jupyter Lab extension

This is a proof-of-concept Jupyter notebook server extension to enable a pre-alpha version of JupyterLab demo.

## Requirements

* npm (preferably version 5 or later)
* Jupyter notebook (version 4.2 or later)

## Installation

```
git clone https://github.com/jasongrout/jupyterlab-extension.git
pip install -e jupyterlab-extension
jupyter serverextension enable --py jupyterlab_extension
```

## Use

Start up the jupyter notebook, and then open a browser to the server's URL with path `/lab` (e.g., `http://localhost:8888/lab`).
