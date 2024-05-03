## Data Science

This repository is a collection of projects in the form of Jupyter notebooks from my DASC 4850: Introduction to Data Science and Analytics in Python I and II class. In these classes, we explored data science, including topics such as: data collection, data wrangling/cleaning, data preprocessing, exploratory data analysis (EDA), statistical analysis, machine learning, model evaluation and tuning, and data visualization.

These projects serve as an introductory exploration of data science techniques, including linear and logistic regression and machine learning. More often than not, I tried to go beyond what was taught in class, and use techniques that we were not explicitly taught. The examples here represent the early stages of my data science journey; reflecting my progression, rather than my current knowledge.

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
