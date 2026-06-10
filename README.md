# Cyclist Traffic ML Project

[![codecov](https://codecov.io/gh/zheddhe/mai25-bds-trafic-cycliste/graph/badge.svg?token=6TLD3FM08Z)](https://codecov.io/gh/zheddhe/mai25-bds-trafic-cycliste)
[![CI Main](https://github.com/zheddhe/mai25-bds-trafic-cycliste/actions/workflows/ci_main.yml/badge.svg)](https://github.com/zheddhe/mai25-bds-trafic-cycliste/actions)
[![CI Branch](https://github.com/zheddhe/mai25-bds-trafic-cycliste/actions/workflows/ci_branch.yml/badge.svg)](https://github.com/zheddhe/mai25-bds-trafic-cycliste/actions)

A machine learning project focused on the analysis and prediction of cyclist traffic patterns in Paris.

Developed as part of the Machine Learning Engineering (MLE) training program, combining Data Product Management, Data Science and MLOps practices.

---

## Overview

This project implements a complete machine learning workflow covering:

### Data Product Management

- Business problem framing
- Data lifecycle definition
- Analytical objective specification

### Data Science

- Data preparation and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model development and evaluation
- Hyperparameter optimization

### MLOps

- Project packaging
- Automated testing
- Continuous Integration
- Reproducibility practices

---

## Project Structure

```text
mai25-bds-trafic-cycliste/
├── app/                    # Streamlit application
├── smartcheck/             # Core project logic
├── tests/                  # Automated tests
├── notebooks/              # Exploratory notebooks
├── README.md
├── LICENSE
├── pyproject.toml
├── noxfile.py
└── .pre-commit-config.yaml
```

---

## Technical Stack

### Data Science

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Statsmodels

### Data Visualization

- Matplotlib
- Seaborn
- Plotly
- GeoPandas

### Application Development

- Streamlit

### Software Engineering & MLOps

- Git
- GitHub Actions
- Pytest
- Codecov
- Nox
- Pre-commit

---

## Streamlit Application

The project includes an interactive Streamlit application allowing:

- Statistical data exploration
- Interactive visualizations
- Model evaluation
- Project presentation
- Analytical result inspection

Launch locally:

```bash
streamlit run app/main.py
```

---

## Testing and Continuous Integration

Testing is implemented using Pytest and includes:

- Unit tests
- Application smoke tests
- Core module validation

Continuous Integration is managed through GitHub Actions and Codecov to ensure code quality and reproducibility.

---

## Contributors

- Rémy Canal – [@remy.canal](mailto:remy.canal@live.fr)
- Elias Djouadi – [@elias.djouadi](mailto:elias.djouadi@gmail.com)
- Raphaël Parmentier – [@pro.raphael.parmentier](mailto:pro.raphael.parmentier@gmail.com)
