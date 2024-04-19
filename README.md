# Description

This is a simple organization templated to be used for multiple Data Science projects, it is a simplified and modified folder structure from the [Cookiecutter Data Science Repository](https://github.com/drivendata/cookiecutter-data-science). 

## How to use

It is suggested to use some form to organize the installation of packages and such, my recomendation is to use a conda manager and create one enviroment for each project. 

```bash
conda create --name ENV_NAME python=3.XX
```

Then activate and install the requirements. 

```bash
conda env ENV_NAME
pip install -r requirements.txt
```

Creating the enviroment and installing the requirements must be done only the first time. 

## Folder structure

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed. (optional)
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
|
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0_jqp_initial-data-exploration`.
│
├── other-programs     <- For saving files from other programs related to the project (QGIS, BI, etc...)
│   ├── subfolder      <- Program A
│   ├── ....           <- ....
|
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── src                <- Source code for use in this project.
```
