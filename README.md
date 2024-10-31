Mushroom Classification Project
Overview

    This project presents 3 classification models to predict whether a mushroom is edible or poisonous based on physical characteristics. Using a dataset of mushroom observations with labeled features, the project compares three machine learning models: logistic regression, k-nearest neighbors, and a decision tree classifier. Ultimately, the decision tree achieved the best results due to its capacity to handle non-linear patterns and categorical data effectively.

Project Goals

    Develop a reliable model to classify mushrooms as edible or poisonous.
    Evaluate and compare different classification algorithms.
    Interpret model performance and provide an explanation for the observed results.

Dataset

    The dataset includes several features relevant to mushroom classification:

    Cap Diameter
    Cap Shape
    Gill Attachment
    Gill Color
    Stem Height
    Stem Width
    Stem Color
    Season

    Each mushroom is labeled as edible or poisonous.

Methods and Models

    Three different classification models were tested on the dataset:

    Logistic Regression: Reached 64% accuracy.
    K-Nearest Neighbors (k=5): Reached 71% accuracy.
    Decision Tree Classifier: Achieved the highest accuracy at 97%.

Explanation of Model Performance

    Logistic Regression and K-Nearest Neighbors showed limited performance, likely due to the linear assumptions and simplicity of these models.
    Decision Tree Classifier outperformed the other models, achieving 97% accuracy. Decision trees can effectively capture non-linear relationships and handle categorical data by recursively partitioning the feature space, making them well-suited for this dataset.

Results and Conclusion

    The decision tree classifier is recommended as the most effective model for this mushroom classification problem, providing high accuracy and intuitive interpretability. In practical applications, such a model could assist in safely identifying mushrooms in ecological or foraging contexts.
