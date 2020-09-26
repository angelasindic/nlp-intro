## Introduction
Examples of simple NLP text classification methods

## Installation
### Python Envirinment Setup
The [Conda Environment Management tool](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) 
is used for dependency management. It requires that conda is already installed.

The provided ```environment.yml``` contains the python libraries needed for the examples.
Create an initial conda virtual environment with:
```
conda env create --file environment.yml
```
This will create a new environment called ```nlp-intro```.

Before continuing the installation, this environment needs to be activated. To activate this environment, use:


```
conda activate nlp-intro
```

An active environment can be deactivated with:

```
conda deactivate
```
### NLTK Installation
The NLTK package uses language data sources which can be installed with:
```
python -m nltk.downloader all
```

### Start jupyter
Start jupyter server locally using default port 8888, this will open a browser window:
```
jupyter notebook
```

## Examples
* [Text classification with SVM and Naive Bayes](text_classification_svm.ipynb)