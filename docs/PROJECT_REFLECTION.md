# Machine Learning – Learning Reflection

## Overview

Machine Learning 600 has helped me understand how computers can learn patterns from data and use those patterns to make predictions or discover structure. The module connects Python programming and data preparation with statistical thinking, model development and evaluation.

## What I found important

One of the most important lessons was that data preparation has a major effect on model performance. Missing values, outliers, inconsistent data and features on very different scales can affect the results. I learned to inspect a dataset before selecting an algorithm and to choose preprocessing methods based on the data and task.

I also developed a clearer understanding of the difference between regression, classification and clustering:
- Regression predicts continuous numerical values.
- Classification predicts categories.
- Clustering discovers groups in unlabelled data.

## Practical lessons

Working through Python examples helped me understand the role of Pandas, NumPy and Scikit-learn. I practised separating features from the target, splitting data into training and testing sets, scaling features and applying PCA.

A particularly important lesson was to fit transformations such as scalers and PCA on the training data only, then use the fitted transformation on the test data. This prevents information from the test set leaking into model training.

I also learned that accuracy is not always the best measure of a classifier. When false negatives are costly, recall can be more informative. The confusion matrix helps explain the types of correct and incorrect predictions rather than hiding them in one score.

## Challenges and areas for improvement

Machine learning requires careful decisions at each stage. It can be difficult to choose an appropriate algorithm, identify the best evaluation metric and interpret why a model performs well or poorly.

To improve, I want to:
- Complete and document end-to-end regression, classification and clustering projects.
- Compare baseline models with tuned models.
- Practise cross-validation and hyperparameter tuning.
- Improve my understanding of feature importance and model interpretation.
- Record reproducible results, including dataset source, random seeds and evaluation metrics.
- Build a stronger understanding of when model assumptions are appropriate.

## Overall reflection

This module has given me a foundation in the machine learning workflow and the importance of evaluating models carefully. I have learned that a good result is not only a high score: it should also generalise to unseen data, use appropriate metrics and be explained honestly.

I plan to keep developing this repository as a portfolio of practical work, adding notebooks and project results as I complete and verify them.
