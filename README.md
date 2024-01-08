# Data Science Salary Classification with Machine Learning Algorithms

### Project Description
This project utilizes machine learning algorithms, specifically the Decision Tree classifier and the K-Nearest Neighbors (KNN) classifier, to predict the "company_size" based on data science salary-related features. By analyzing a dataset containing information about data science salaries, features such as years of experience, education level, and job title are examined for their relationship with company size. The Decision Tree classifier is employed using both Gini Index and Entropy criteria, while the KNN classifier is trained on a split dataset and evaluated for accuracy. The project provides code implementation in Python using libraries such as scikit-learn, numpy, and matplotlib, aiming to offer a reliable and interpretable solution for predicting company size in the data science domain.

### Data source
Kaggle: https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries/data

### Objective
The objective of the Data Science Salary Classification project is to develop machine learning models that can accurately predict the "company_size" based on various features related to data science salaries. By utilizing the Decision Tree and K-Nearest Neighbors (KNN) classifiers, the project aims to analyze the relationship between factors like years of experience, education level, and job title with company size. The project seeks to provide insights into the performance and interpretability of different machine learning algorithms in this specific context. Ultimately, the project aims to create a reliable and practical tool for predicting company size from data science salary-related features, contributing to a better understanding of the factors influencing company size in the data science industry.

### Result and Insight
- Decision Tree Classifier:
  - Gini Index: Accuracy of approximately 66.12% in predicting "company_size" based on data science salary-related features.
  - Entropy: Accuracy of approximately 67.21% in predicting "company_size".
  - The model struggled with accurately predicting instances in the third category (label 2).
  - Varied performance across different categories.
  - Precision, recall, and F1-scores calculated for each category.

- K-Nearest Neighbors (KNN) Classifier:
  - Accuracy of around 45.08% in predicting "company_size" on the test set.
  - Predicted values for the test dataset presented as an array.
  - Model's overall accuracy measured using the `score()` function.

Insights:
- Moderate accuracy achieved by both the Decision Tree and KNN classifiers.
- The Decision Tree model provided interpretability but had limitations in accurately predicting certain categories.
- The KNN model showed lower accuracy compared to the Decision Tree model.
- Further analysis, feature engineering, and exploration of other algorithms may improve performance.
- Insights gained contribute to understanding factors influencing company size in the data science industry.
