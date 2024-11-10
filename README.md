# Methods
A template for data science projects.

## Introduction

Methods provides a template that is suitable for some data data science projects.  It consists of `materials`, `methods`, and `results` directories.  The `pyproject.toml` is configured to install the `methods` directory as a Python package.

## Usage

### Clone the repository.
```bash
git clone https://github.com/faranalytics/methods.git
```

### Change directory into the respository.
```bash
cd methods
```

### Install the package in editable mode.
```bash
pip install -e .
```

### Import a module.

#### Open a Notebook.

Open the `methods/main.ipynb` Notebook.

#### Import the `say_hello` function from the `utils` module.

```python
from methods.utils import say_hello
```