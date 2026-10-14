<div align="center">

# Diabetes Type Classification with Machine Learning

**Comparing 7 classic ML models to classify 13 diabetes types from 33 clinical, genetic, and lifestyle features.**

![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

</div>

---

## Overview

This project explores a **70,000-record diabetes dataset** and trains several supervised learning models to predict the **type of diabetes** (multiclass, 13 classes). Features include genetic markers, autoantibodies, family history, insulin levels, age, BMI, blood pressure, glucose levels, lifestyle factors, and more.

The notebook covers the full workflow: data exploration, visualization, preprocessing, model training, and comparison.

## Workflow

1. **Exploratory data analysis:** dataset shape, missing values, duplicates, class distribution
2. **Visualization:** age and insulin distributions, age by diabetes type, correlation heatmap, feature histograms
3. **Preprocessing:** label encoding for categorical features, standard scaling for numerical features
4. **Train/test split:** 80/20 (56,000 / 14,000 samples)
5. **Model training & evaluation:** accuracy comparison across 7 classifiers

## Results

| Model | Accuracy |
| --- | --- |
| **Random Forest** | **90.0%** |
| Gradient Boosting | 89.9% |
| Decision Tree | 86.2% |
| Naive Bayes | 82.6% |
| Support Vector Machine | 80.2% |
| Logistic Regression | 76.0% |
| K-Nearest Neighbors | 64.5% |

Ensemble methods (Random Forest and Gradient Boosting) performed best on this dataset.

## Tech Stack

| Purpose | Tools |
| --- | --- |
| Language | Python |
| Data handling | pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine learning | scikit-learn |
| Environment | Jupyter / Google Colab |

## Getting Started

```bash
git clone https://github.com/Nussssu/Diabetes-Classification-with-ML.git
cd Diabetes-Classification-with-ML
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook "project Code.ipynb"
```

> The notebook was written for Google Colab and loads the dataset from Google Drive. To run it locally, rename `diabetes_dataset00.csv.crdownload` to `diabetes_dataset00.csv` and update the `pd.read_csv(...)` path in the notebook. Skip the `drive.mount(...)` cell.

## Repository Contents

| File | Description |
| --- | --- |
| `project Code.ipynb` | Full analysis and model training notebook |
| `diabetes_dataset00.csv.crdownload` | Diabetes dataset (CSV) |

## Author

**Nusrat Jahan Ankhi** · [GitHub](https://github.com/Nussssu)
