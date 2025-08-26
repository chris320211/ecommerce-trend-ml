This project builds a machine learning pipeline to predict user purchasing behavior on an e-commerce platform. Using a large Kaggle dataset with 2+ million logged events, I engineered features from raw clickstream data and trained a classification model with XGBoost, handled severeclass imbalance, tuned parameters to maximize F1, and achieved an F1-score of 0.74.

Source: https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

Dataset Used: 2019-Oct.csv

Model Used: XGBoost Classifier

Technology Used: Google Cloud: 8vCPUs, 32 GB RAM

## 📦 Core ML Tools, Libraries, and Visualization Tools Used

- [pandas](https://pandas.pydata.org/) – data manipulation and analysis
- [numpy](https://numpy.org/) – numerical computing
- [scikit-learn](https://scikit-learn.org/) – ML utilities, evaluation metrics, confusion matrix
- [xgboost](https://xgboost.readthedocs.io/) – gradient boosting model
- [matplotlib](https://matplotlib.org/) – visualizations (metrics chart, PR curve)
- [seaborn](https://seaborn.pydata.org/) – enhanced plots and heatmaps

## 📊 Results

| Metric      | Score |
|-------------|-------|
| Accuracy    | 0.992 |
| Precision   | 0.799 |
| Recall      | 0.697 |
| **F1-score** | **0.745** |
