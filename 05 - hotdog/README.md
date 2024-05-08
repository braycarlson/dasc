## Hotdog or Not Hotdog

This is a collaborative data science project between [Angela De Sousa Costa](https://github.com/angeladesousacosta) and [Brayden Carlson](https://github.com/braycarlson) from our DASC 4850: Introduction to Data Science and Analytics in Python II class. You can view the code and output by opening the `hotdog.ipynb` notebook on GitHub.

## Prerequisites

* [pyenv](https://github.com/pyenv/pyenv) or [Python 3.11.2](https://www.python.org/downloads/)

### Windows

* https://graphviz.org/download/#windows

### Linux (Debian)

```
sudo apt install graphviz graphviz-dev
```

## Setup

### pyenv

```
pyenv install 3.11.2
```

```
pyenv local 3.11.2
```

### Virtual Environment

```
python -m venv venv
```

#### Windows

```
"venv/Scripts/activate"
```

#### Unix

```
source venv/bin/activate
```

### Packages

```
pip install -U -r requirements.txt && pip install -U -r local.txt
```
