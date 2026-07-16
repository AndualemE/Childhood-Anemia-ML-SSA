# Explainable Machine Learning for Predicting Childhood Anemia in Sub-Saharan Africa Using Population-Based DHS Data (2016–2024)

## Overview

This repository contains the Python notebook and supporting code used in the study:

**Explainable Machine Learning for Predicting Childhood Anemia in Sub-Saharan Africa Using Population-Based DHS Data (2016–2024)**

The study developed and compared eight machine learning algorithms to predict childhood anemia among children aged 6–59 months using pooled Demographic and Health Survey (DHS) data from 26 Sub-Saharan African countries.

The evaluated machine learning models include:

- Logistic Regression
- Decision Tree
- Random Forest
- Extra Trees
- XGBoost
- LightGBM
- CatBoost
- Multi-Layer Perceptron (MLP)

Model interpretation was performed using SHAP (SHapley Additive exPlanations).

---

## Repository Contents

```
.
├── model_training.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Data Availability

The Demographic and Health Survey (DHS) datasets are **not included** in this repository because redistribution is not permitted by the DHS Program.

Researchers may request access to the datasets from:

https://www.dhsprogram.com/data/

After approval, place the downloaded datasets in your local working directory and update the file paths in the notebook if necessary.

---

## Software Requirements

- Python 3.12 (or later)

Required packages are listed in **requirements.txt**.

Install them using

```bash
pip install -r requirements.txt
```

---

## Running the Analysis

Open the notebook

```
model_training.ipynb
```

and execute the cells sequentially.

The notebook performs:

1. Data preprocessing
2. Missing value imputation
3. Feature engineering
4. Train–test split
5. Hyperparameter tuning
6. Model training
7. Model evaluation
8. ROC curve generation
9. Calibration analysis
10. SHAP explainability analysis

---

## Citation

If you use this repository, please cite:

Gedefaw AE, Worku A, Mengistu AK, Terefe B, Taye EA, Kebede FB, et al.

Explainable Machine Learning for Predicting Childhood Anemia in Sub-Saharan Africa Using Population-Based DHS Data (2016–2024).

PLOS Global Public Health.

---

## Contact

Corresponding Author

**Andualem Enyew Gedefaw**

Department of Health Informatics

University of Gondar

Email:
andualemenyew@gmail.com
