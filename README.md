# Machine Learning Portfolio

A learning portfolio documenting my study and practical work in **Machine Learning 600** as part of my BSc Information Technology studies.

This repository is intended to bring together my notes, Python exercises, experiments, model evaluations and reflections as I develop my understanding of machine learning.

> **Repository status:** The repository currently contains its introductory documentation. Practical notebooks, datasets and project-specific results will be added as they are organised and verified.

## Learning areas

The module introduces the machine learning workflow, from understanding data and preparing features to training and evaluating models.

| Topic | What I am learning |
|---|---|
| Introduction to Machine Learning | What ML is, how it differs from traditional programming, and common applications |
| Data Preprocessing | Structured and unstructured data, missing values, duplicates and outliers |
| Feature Engineering | Feature selection, scaling, normalization and preparing model inputs |
| Dimensionality Reduction | Principal Component Analysis (PCA) and explained variance |
| Supervised Learning – Regression | Linear, polynomial and decision tree regression |
| Supervised Learning – Classification | Logistic regression, k-nearest neighbours and support vector machines |
| Unsupervised Learning | Clustering with K-Means, DBSCAN and hierarchical clustering |
| Model Evaluation | Train/test split, accuracy, precision, recall, F1-score, R² and MAE |
| Model Improvement | Overfitting, bias–variance trade-off and hyperparameter tuning |

## Tools and technologies

- **Python** – implementation and experimentation.
- **Pandas** – loading, inspecting and manipulating datasets.
- **NumPy** – numerical operations and data preparation.
- **Matplotlib / Seaborn** – data visualisation.
- **Scikit-learn** – preprocessing, model training and evaluation.
- **Jupyter Notebook** – documenting experiments (where used).

## Concepts and practical skills

### Data preparation
- Inspecting dataset dimensions, columns and data types.
- Handling missing values using deletion or imputation where appropriate.
- Identifying duplicates and investigating outliers.
- Separating input features (X) from the target variable (y).
- Scaling features with techniques such as MinMaxScaler and standardization.
- Avoiding data leakage by fitting preprocessing steps on training data only.

### Model development
- Splitting data into training and test sets.
- Training supervised learning models for continuous and categorical targets.
- Applying PCA to reduce feature dimensions.
- Comparing model performance using appropriate evaluation metrics.
- Understanding why a model may overfit and how to improve generalisation.

### Evaluation and interpretation
- Confusion matrix: true positives, true negatives, false positives and false negatives.
- Precision: how many positive predictions were correct.
- Recall: how many actual positive cases were identified.
- F1-score: the balance between precision and recall.
- R² and Mean Absolute Error (MAE) for regression tasks.

## Repository structure

The structure below is the planned organisation as practical work is added:

```text
Machine-Learning/
│
├── README.md
│
├── docs/
│   ├── LEARNING_OUTCOMES.md
│   └── PROJECT_REFLECTION.md
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_pca_dimensionality_reduction.ipynb
│   ├── 03_regression_models.ipynb
│   ├── 04_classification_models.ipynb
│   └── 05_clustering_models.ipynb
│
├── datasets/
│
├── src/
│
└── images/
```

Only the documentation files are currently committed. The folders and notebook names above describe the intended organisation; they are not claimed to exist yet.

## How I approach a machine learning task

1. Understand the problem and identify the target to predict or pattern to explore.
2. Load and inspect the dataset.
3. Clean the data and prepare the features.
4. Split data into training and test sets.
5. Fit preprocessing transformations using training data only.
6. Train a suitable baseline model.
7. Evaluate it with metrics appropriate to the task.
8. Interpret the results, identify limitations and improve the approach.

## What I am learning

Through this module, I am developing the ability to:
- Explain the differences between supervised, unsupervised and reinforcement learning.
- Prepare datasets for machine learning.
- Select and scale useful features.
- Apply PCA and understand explained variance.
- Build regression and classification models.
- Explore clustering algorithms.
- Evaluate model performance and recognise overfitting.
- Interpret results and communicate limitations.

A fuller breakdown is available in [Learning Outcomes](docs/LEARNING_OUTCOMES.md), with a personal [Project Reflection](docs/PROJECT_REFLECTION.md).

## Academic context

**Module:** Machine Learning 600  
**Programme:** BSc Information Technology  
**Purpose:** A personal learning and practical-work portfolio supporting my academic development.

The concepts documented here are being studied using the Machine Learning 600 study guide and practical exercises. Individual datasets, code, results and external resources will be credited in the relevant project folders as they are added.

## Author

**Denzel L. Zimidzi**  
GitHub: [@denzelliljuice27-png](https://github.com/denzelliljuice27-png)

---

*This repository is a work in progress. Content will be expanded as practical exercises and projects are completed and reviewed.*
