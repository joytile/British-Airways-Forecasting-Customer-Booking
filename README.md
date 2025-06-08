# Forecasting British Airways' Customer Booking
![GitHub](https://img.shields.io/badge/Language-Python-blue)
![GitHub](https://img.shields.io/badge/Model-Voting_Classifier-purple)
![GitHub](https://img.shields.io/badge/Library-Scikit_Learn-Green)

## Project Overview


## Key insights💡
- Purchase lead, the number of days between travel date and booking date is the most influential feature in this model. 

## Rceommendations 👌

## Dataset 📂

## Methodology 
### 1. Exploratory Data Analysis 🔭
- **Descriptive Statistics**: Examining the characteristics of the data
- **Variable Analysis**: Visualizing distributions of features to uncover patterns
  

### 2. Data Preprocessing and Feature Engineering 🛠️
- **Outlier Handling**: Handling outliers using logarithmic transformation on positively skewed features.
- **Variable encoding**: Encoding boolean and other categorical variables, using one hot encoding, to allow the model understand them.
- **Creating new features**: Engineered new features to contribute to predictive power of the model
- **Dropping features**: Removed features that showed low correlation with the target variable or contributed little to model performance.
### 3. Model Development
- **Hyperparameter Tuning**: Tuning the model with optuna to maximize F1-score
- **Class Balancing**: Balancing the severely imbalanced target variable, churn.
- **Ensemble Model**: Combined LightGBM and Random forest Classifiers using Voting Classifier to improve model robustness.
### 4. Model Evaluation
- **Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix


