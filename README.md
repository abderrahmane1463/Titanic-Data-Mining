<h1 align="center">Titanic Data Mining</h1>

<p align="center">
  <em>Survival prediction on the Titanic dataset using exploratory data analysis and a Decision Tree classifier</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/matplotlib-11557C?style=flat-square"/>
</p>

---

## Overview

A data mining project applying supervised classification to the Kaggle Titanic dataset (891 passengers). The notebook covers the complete pipeline — data cleaning and feature engineering, exploratory analysis to surface survival patterns, and a Decision Tree classifier evaluated with a confusion matrix and full classification report. The decision tree is visualised to make the model's survival logic interpretable.

## Features

- Data cleaning: missing value handling, feature encoding, and preprocessing
- Exploratory Data Analysis (EDA): survival rates by gender, class, age, and embarkation port
- Decision Tree classifier trained with the entropy criterion
- Model evaluation: accuracy score, confusion matrix, and classification report
- Decision tree visualisation for interpretability
- Full PDF report included alongside the notebook

## Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Modelling | scikit-learn (Decision Tree) |
| Data Analysis | pandas, numpy |
| Visualisation | matplotlib |
| Notebook | Jupyter |
| Dataset | Kaggle Titanic Dataset (891 observations) |

## Project Structure

```
Titanic-Data-Mining/
├── titanic_data_mining.ipynb   # Full analysis notebook
├── titanic.csv                 # Dataset (891 passengers)
├── decision_tree.png           # Visualised decision tree
└── titanic_report.pdf          # Written project report
```

## Results / Key Insights

- Gender is the strongest predictor of survival — female passengers survived at significantly higher rates across all passenger classes
- Passenger class (Pclass) is the second most important feature, with first-class passengers having a clear survival advantage over third-class
- The Decision Tree classifier achieves solid accuracy on the test set, and the visualised tree confirms that the model has learned human-readable survival rules consistent with historical accounts of the disaster

---

<p align="center">Made by <a href="https://github.com/abderrahmane1463">Cherfaoui Houssam Abderrahmane</a></p>
