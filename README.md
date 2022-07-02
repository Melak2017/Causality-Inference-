# Breast cancer prediction using causal Inference.

## Content

- [Overview](#overview)
- [Dataset Description](#the-dataset-description)
- [Install](#install)
- [Project Structure](#project-structure)

---

## Overview

## The Dataset Description

- Diagnosis: The diagnosis of breast tissues (M = malignant, B = benign)
- Radius mean: mean of distances from center to points on the perimeter
- Texture mean: standard deviation of gray-scale values
- Perimeter_mean: mean size of the core tumor
- Area_mean
- Smoothness_mean: mean of local variation in radius lengths
- Compactness_mean: mean of $(perimeter^2 / area - 1.0)$
- Concavity_mean: mean of severity of concave portions of the contour
- concave points_mean: mean for number of concave portions of the contour

## Install

```
clone https://github.com/Melak2017/Causality-Inference-
pip install -r requirements.txt
```

---

## Project Structure

    .
    ├── .github/workflows              # github actions
    ├── .vscode                        # collection of folders that are opened in a VS Code window.
    ├── .dvc                           # for data versioning.
    ├── data                           # data directory
    ├── logs                           # log files
    ├── notebooks                      # directory contaning notebok files.
    │   ├── causal_analysis.ipynb      # notebook containing causal infrerence explanatory analysis.
    │   ├── data_analysis.ipynb        # notebook for explanatory data analysis of the dataset.
    │   └── data_cleaning              # notebook for data cleaning and preparation.
    │
    ├── screenshots                    # A sample screenshots of analysis result.
    ├── scripts                        # script files.
    |    ├── data_cleaner.py           # a python script for cleaning pandas dataframes.
    │    ├── data_loader.py            # a python script for loading csv and excel files to a dataframe.
    │    ├── data_preview.py           # a python script for to geting information about the data.
    │    ├── plots.py                  # a python script for plotting dataframes.
    │    └── ScalarNormalizer.py       # a python script for normalizing model feature.
    |
    ├── tests                          # directory for unit testing
    |    └── test_get_preview.py       # unit-test file
    ├── requirements.txt               # a text file lsiting the projet's dependancies
    ├── .gitignore                     # files to ignore when committing
    ├── setup.py                       # a configuration file for installing the scripts as a package
    ├──LICENSE                         # license file
    ├── .dvcigonre                     # files to ignore when committing
    └── README.md                      # Markdown text with explanation of the project and the structure.

---

[back to top](#content)
