# Health Classification Project

## Overview

This project aims to explore and analyze health-related data, specifically focusing on the impact of age, gender, smoking habits, and weight status on health risk classification. The dataset used for this analysis was generated synthetically for illustrative purposes.

## Data Generation

Random data was generated for age, gender, smoking status, and weight status. The dataset was then enriched with a health risk classification, creating a balanced dataset of 50 samples.

### Data Attributes

- **Age**: Age of the individuals (integer).
- **Gender**: Gender of the individuals (categorical: Male/Female).
- **Smoking**: Smoking habits of the individuals (categorical: Yes/No).
- **Weight Status**: Weight status of the individuals (categorical: Normal/Overweight/Obese).
- **Risk**: Health risk classification (categorical: Low Risk/Medium Risk/High Risk).

## Exploratory Data Analysis (EDA)

Exploratory data analysis was performed to understand the distribution of variables and their correlations. Key visualizations include:

- Gender distribution pie chart.
- Smoking habits bar chart.
- Weight status distribution bar chart.
- Health risk distribution bar chart.

## Health Status Analysis

An analysis of health status was performed for specific subgroups:

1. **Obese Smokers**: Health status of individuals who are both obese and smoke.
2. **Non-Smokers with Normal Weight**: Health status of non-smokers with normal weight.

## Machine Learning Models

Several machine learning classification models were implemented to predict health risk based on the given features:

1. **Random Forest Classifier**: Achieved an accuracy of 20%.
2. **Decision Tree Classifier**: Achieved an accuracy of 40%.
3. **Support Vector Machines (SVM)**: Achieved an accuracy of 40%.
4. **k-Nearest Neighbors (k-NN)**: Achieved varying accuracies with different values of k.
5. **Logistic Regression**: Achieved an accuracy of 40%.

### Model Tuning

- For k-NN, different values of k (neighbors) were tested, and their impact on accuracy was analyzed.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Future Work

- Fine-tune hyperparameters for better model performance.
- Explore more advanced machine learning models.
- Incorporate a larger and more diverse dataset for robust analysis.

## Author

Talha Çerçioğlu

Feel free to fork, modify, and use this template for your projects. Happy coding!
