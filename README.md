Mushroom Classification – Binary Classification with Numerical Features
Overview

This project demonstrates a complete binary classification pipeline to distinguish between edible and poisonous mushrooms based on numerical features. It simulates a real-world request and is fully transferable to applications in healthcare, food safety, or life sciences.

Three models were trained and compared: Logistic Regression, K-Nearest Neighbors, and Decision Tree. Each model was evaluated using multiple performance metrics and feature importance analyses.


Objectives

    Build reliable machine learning models to classify mushrooms as edible or poisonous

    Evaluate and compare model performance using accuracy, ROC curves, and confusion matrices

    Analyze and interpret feature importance across models

    Provide transparent and reproducible results for use in real-world applications


Dataset

The dataset contains only numerical features, including characteristics such as:

    Cap Diameter

    Cap Shape

    Gill Attachment

    Gill Color

    Stem Height

    Stem Width

    Stem Color

    Season

Each mushroom is labeled as edible (0) or poisonous (1). The data was balanced, and standard scaling was applied to ensure fair model comparison.

Models and Methods

Three machine learning models were implemented:
Model	Accuracy	AUC	Remarks
Logistic Regression	63.9%	~0.68	Linear, interpretable, but limited fit
KNN (k = 5)	96.9%	~0.99	High performance, distance-based
Decision Tree	95.5%	~0.95	Non-linear, interpretable, fast

Each model was evaluated using:

    Confusion matrices

    ROC curves

    Precision, recall, F1-score

    Feature importance (via coefficients, Gini, or permutation)

Key Insights

    KNN performed best in terms of accuracy and AUC, indicating strong class separation in feature space.

    Decision Tree offered high accuracy with interpretable structure and feature rankings.

    Logistic Regression served as a useful baseline but was limited by its linearity.

    Feature importance was consistent across models, confirming robust predictors.

Visualizations Included

    ROC curve comparison for all models

    Confusion matrix side-by-side plot

    Bar plot and heatmap of feature importance

    Correlation matrix for preprocessing

Conclusion

This project highlights how different models handle the same classification task with varying levels of accuracy, interpretability, and computational complexity. The results offer guidance for selecting suitable models depending on the problem context and data type.

    A similar methodology was successfully applied in a real Fiverr project analyzing cryptocurrency market patterns.
