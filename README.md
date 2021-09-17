# sphinx-docs

Generating documentation with Sphinx.

## Getting Started

```sh
# Create a virtual environment
python -m venv venv

# Activate the virtual environment (Linux)
source venv/bin/activate

# Activate the virtual environment (Windows)
venv\Scripts\activate

# Change path
cd docs
```

## Install Requirements

```sh
pip install pylint black
pip install -U Sphinx
pip install sphinx-autobuild
```

## Init Sphinx Project

```sh
sphinx-quickstart
```

Configuration terms: https://www.sphinx-doc.org/en/master/usage/configuration.html

## Build Docs

```sh
# Export to html
make html

# Automatically watch the changes in a running server
sphinx-autobuild . ./_build/html
```
