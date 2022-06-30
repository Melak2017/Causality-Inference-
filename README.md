# Breast cancer prediction using causal Inference.

## Background

The USGS 3DEP project (United States Geological Survey 3D Elevation Program) aims at responding to growing needs for high-quality topographic data and a wide range of 3D data representation of the county’s features.

## Content

- [Overview](#overview)
- [Dataset Description](#the-dataset-description)
- [Install](#install)
- [Project Structure](#project-structure)

- [Dashboard](#dashboard)
- [Article](#article)

---

## Overview

## The Dataset Description


---

## Install


```
clone https://github.com/Melak2017/AgriTech-Lidar-data.git
pip install -r requirements.txt
```

---

## Project Structure

    .
    ├── .github/workflows              # github actions
    ├── .vscode                        # collection of folders that are opened in a VS Code window.
    ├── assets
    |   └──data_fetch.json             # pipline json file
    |
    ├── data                           # data directory
    ├── docs                           # HTML pages
    ├── notebooks                      # A simple - notebook on how to use the package.
    ├── screenshots                    # A sample screenshots of analysis result.
    ├── scripts                        # script files.
    |    ├── boundaries.py             # python file for boundry setting
    │    ├── ept_info.py               # pyhon file for info ept
    │    ├── elevation_extractor.py    # python file elevation extractor
    │    ├── lidar_fetch_data.py       # python file for data fecthing
    │    └── Lidar_Package.py          # final python module to use
    |
    ├── tests                          # directory for unit testing
    |    └── test_get_data.py          # unit-test file
    ├── requirements.txt               # a text file lsiting the projet's dependancies
    ├── .gitignore                     # files to ignore when committing
    ├── setup.py                       # a configuration file for installing the scripts as a package
    └── README.md                      # Markdown text with explanation of the project and the structure.

---

[back to top](#background)
