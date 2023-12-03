
## Credit Card Fruad Detection

This repository contains Jupyter notebooks dedicated to individual dataset of Credit Card Fraud Detection from Kaggle, each performing a series of tasks:

1. **Data Retrieval and Exploration**:
   - Download or fetch data using `urllib`.
   - Utilize `head()` to glimpse the data structure.
   - Use `describe()` to understand feature scales.
   - Generate histograms for each feature.
   - Plot pairwise scatter plots to explore relationships between features.
   - Calculate pairwise correlations to analyze feature relationships.

2. **Data Preparation**:
   - Remove unnecessary columns from the datasets.
   - Fill missing values using `sklearn.impute`.
   - Encode categorical data to numerical (if required) using `sklearn.preprocessing`.
   - Apply appropriate feature scaling techniques.

3. **Pipeline Execution**:
   - Use transformation pipelines to execute tasks in a sequential order.

4. **Model Training**:
   - Split data into test and train sets.
   - Train models on training datasets.

5. **Hyperparameter Tuning**:
   - Employ `GridSearchCV` or `RandomizedSearchCV` to fine-tune important hyperparameters.

6. **Performance Evaluation**:
   - Assess model performance using confusion matrices.
   - Discuss Precision and Recall metrics.
   
