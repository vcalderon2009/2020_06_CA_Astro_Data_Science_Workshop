[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vcalderon2009/2020_06_CA_Astro_Data_Science_Workshop/master)

CA Astro - Data Science and Machine Learning Workshop
==============================

    Tutorials and notebooks dedicated towards teaching about Data Science and Machine Learning

| | |
|---------------|---------------------------------------------------|
| __Author__    | Victor Calderon [[homepage](http://vcalderon.me)] |
| __Dates__     | 13th and 14th of June, 2020                       |
| Documentation | Link |


## Description

The following set of tutorials form part of the "Tutorials Series" hosted by
"[Central American - Caribbean Bridge in Astrophysics Program](https://cencabridgeastro.weebly.com/)".

In these tutorials, we will cover how to:

- Extract datasets
- Perform exploratory data analysis (EDA) of the datasets. This includes
    1. Extract summary statistics about the dataset
    2. Clean the datasets
    3. Transform columns to useful *features*
- Define and *train* a machine learning (ML) model using out-of-the-box utilities from Python packages.
- Determine the performance of the ML model

We will also discuss some common practices when dealing with ML models, as EDA best practices.



Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
