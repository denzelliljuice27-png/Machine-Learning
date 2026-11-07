# Machine Learning – Learning Outcomes

This document summarises the concepts and practical skills I am developing through Machine Learning 600. It is a learning record, not a claim that every listed algorithm has already been implemented in a completed project.

## 1. Understanding machine learning

I learned that machine learning is a branch of artificial intelligence in which algorithms learn patterns from data to make predictions or decisions. Unlike traditional programming, where rules are explicitly written, an ML model learns relationships from examples during training.

I am studying the three main learning approaches:
- **Supervised learning:** learns from labelled examples. Examples include predicting house prices and classifying spam.
- **Unsupervised learning:** explores unlabelled data to discover groups or structure, such as customer clustering.
- **Reinforcement learning:** an agent learns by interacting with an environment and receiving rewards or penalties.

## 2. Data preprocessing and feature engineering

I learned why data quality matters before training a model. Topics include:
- Understanding structured and unstructured data.
- Inspecting rows, columns, data types and summary statistics.
- Identifying missing values, duplicates and outliers.
- Choosing when to remove records and when to impute missing values.
- Separating input features (X) from the target (y).
- Understanding feature selection and feature engineering.

I also studied feature scaling:
- **Normalization / Min-Max scaling:** maps values to a specified range, commonly 0 to 1.
- **Standardization:** transforms values using the mean and standard deviation.

Scaling is important for algorithms affected by feature magnitude, such as KNN, SVM and many gradient-based methods. Tree-based models generally do not require feature scaling.

## 3. Principal Component Analysis (PCA)

I learned that PCA is a dimensionality-reduction technique that transforms correlated features into a smaller set of principal components.

Important ideas:
- Components are ordered by the amount of variance they explain.
- Explained variance ratio helps decide how many components to retain.
- PCA can reduce dimensionality and redundancy, but components may be less interpretable than original features.
- Features are commonly standardized before PCA when they use different scales.
- PCA must be fitted on training data only; the fitted transformation is then applied to test data to avoid data leakage.

## 4. Supervised learning – regression

Regression predicts a continuous numerical value.

Models covered in the module include:
- **Linear Regression:** models a linear relationship between features and a continuous target.
- **Polynomial Regression:** adds polynomial feature terms to represent curved relationships.
- **Decision Tree Regression:** predicts values using a sequence of feature-based splits.

Evaluation concepts:
- **R² score:** indicates how much variation in the target is explained by the model relative to a baseline.
- **Mean Absolute Error (MAE):** average absolute difference between predictions and actual values.

I also studied the bias–variance trade-off and why overly complex models can overfit.

## 5. Supervised learning – classification

Classification predicts a category or class label.

Algorithms studied include:
- Logistic Regression.
- k-Nearest Neighbours (KNN).
- Support Vector Machines (SVM).
- Decision Trees and Random Forests.
- Naive Bayes.

Evaluation concepts:
- **Accuracy:** proportion of all predictions that are correct.
- **Precision:** proportion of predicted positives that are truly positive.
- **Recall:** proportion of actual positives correctly identified.
- **F1-score:** harmonic mean of precision and recall.
- **Confusion matrix:** counts true positives, true negatives, false positives and false negatives.

I learned that the best metric depends on the problem. For example, recall is especially important when missing a true positive case has a high cost.

## 6. Unsupervised learning – clustering

Clustering groups observations based on similarity without requiring labelled target values.

Methods studied:
- **K-Means:** assigns observations to a chosen number of clusters based on distance to cluster centres.
- **DBSCAN:** groups dense regions and can identify noise points; it does not require the number of clusters to be specified in advance.
- **Hierarchical clustering:** builds a hierarchy of clusters that can be examined using a dendrogram.

I learned that clustering results require interpretation and that different algorithms can produce different groupings.

## 7. Model workflow and responsible evaluation

A reliable model workflow includes:
1. Define the problem and target.
2. Inspect and prepare the data.
3. Split into training and test sets.
4. Fit preprocessing steps on training data only.
5. Train a baseline model.
6. Evaluate on data not used for fitting.
7. Compare models using suitable metrics.
8. Investigate errors, limitations and possible improvements.

I learned that overfitting occurs when a model learns training data too closely and performs poorly on unseen data. A train/test split, cross-validation, regularisation, simpler models and tree-depth limits can help reduce this risk.

## 8. Practical skills developed

The practical exercises and coursework have helped me practise:
- Python data handling with Pandas and NumPy.
- Identifying and preparing features and targets.
- Train/test splitting with Scikit-learn.
- Scaling data with MinMaxScaler.
- Applying PCA and interpreting explained variance.
- Evaluating classification with a confusion matrix and recall.
- Understanding regression and clustering workflows.
- Recognising data leakage and overfitting risks.

## Personal takeaway

The main lesson is that building a machine learning model is not just choosing an algorithm. The quality of the data, preprocessing decisions, evaluation metric and interpretation of results all affect whether a model is useful. I am continuing to strengthen these skills through practical implementations and documented experiments.
