# Data Science ARA 7.0

A comprehensive **Data Science competition project repository** for **ARA 7.0**, built using both **Python (Jupyter Notebook)** and **R** to explore multiple modeling strategies, compare performance, and optimize leaderboard results.

---

## Project Overview
This repository contains the end-to-end workflow for solving the **Data Science ARA 7.0 competition problem**, including:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Model development
- Cross-validation
- Performance comparison
- Final submission generation

The project intentionally uses **two ecosystems**:

- **Python** → fast experimentation, notebook-based workflow, machine learning pipeline
- **R** → statistical exploration, alternative modeling, benchmarking

This dual-language approach helps compare insights and improve model robustness.

---

## Repository Structure
```bash
Data-Science-ARA-7.0/
│
├── data-science-ara-7-0.ipynb   # Main Python notebook workflow
├── data-science-ara-7-0-r.r     # Alternative R-based modeling pipeline
└── README.md                    # Project documentation
```

---

## Workflow
The modeling pipeline follows this general workflow:

```text
Business Understanding
        ↓
Exploratory Data Analysis
        ↓
Data Cleaning & Preprocessing
        ↓
Feature Engineering
        ↓
Model Training
        ↓
Cross Validation
        ↓
Hyperparameter Tuning
        ↓
Ensemble / Final Submission
```

---

## Key Methodology
### 1) Exploratory Data Analysis
- Dataset shape and schema inspection
- Missing value analysis
- Target distribution analysis
- Correlation exploration
- Outlier detection
- Feature importance intuition

### 2) Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Scaling numerical features
- Train-validation split
- Leakage prevention

### 3) Feature Engineering
- Interaction features
- Aggregated statistical features
- Time-based / grouped features (if applicable)
- Domain-driven transformations

### 4) Modeling
The repository is designed to support multiple models such as:

- LightGBM
- XGBoost
- Random Forest
- Logistic Regression
- CatBoost
- R-based statistical / ML models

### 5) Validation Strategy
- Stratified K-Fold Cross Validation
- Metric-based optimization
- Public vs Private leaderboard gap analysis

---

## Tech Stack
### Python
- pandas
- numpy
- scikit-learn
- lightgbm
- xgboost
- matplotlib
- seaborn

### R
- tidyverse
- caret
- xgboost
- data.table
- tidymodels

---

## Results
> Update this section with your best competition score.

Example:

```text
Best Cross Validation Score : 0.9123
Public Leaderboard         : Top 15%
Private Leaderboard        : Top 20%
```

---

## How to Run
### Python Notebook
```bash
jupyter notebook data-science-ara-7-0.ipynb
```

### R Script
```r
source("data-science-ara-7-0-r.r")
```

---

## Project Highlights
- Multi-language experimentation (**Python + R**)
- Competition-focused workflow
- Reproducible notebook pipeline
- Flexible feature engineering framework
- Easy benchmarking between ecosystems

---

## Future Improvements
- Add modular `src/` pipeline
- Add automated experiment tracking
- Add Optuna hyperparameter tuning
- Add ensemble stacking
- Improve feature selection pipeline
- Add final submission artifacts

---

## Author
**Dimas Pasha Akrilian**

If you find this project useful, feel free to star the repository and connect for collaboration in **data science, machine learning, and competition projects**.

