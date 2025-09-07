# Machine-Learning-Predicting-Breast-Cancer-Survival-Outcomes

Machine Learning project to predict breast cancer survival outcomes.

This repository contains my coursework for the Machine Learning and Data Mining module. The project demonstrates both classification and regression approaches to predict patient survival outcomes and survival duration

Libraries used:

- **`pandas`** – for loading, cleaning, and exploring structured datasets
  
- **`matplotlib`** – for generating visualisations and plots
  
- **`nummpy`** – for numerical computations and array operations
  
- **`scikit-learn`** – for implementing machine learning models including Logistic Regression, Naïve Bayes, KNN, Ensemble Voting, and Decision Tree regressors

Contents include:
- Report that summarises findings from both classification and regression tasks, including visualisations, performance metrics, and key predictors.

- Notebooks – Python notebooks demonstrating preprocessing, model building, and evaluation steps
  
  Notebook 1 Prepares the raw breast cancer dataset for analysis by handling missing values, encoding categorical variables (e.g., tumour stage, hormone status), and normalising numerical features. Explores the dataset through descriptive statistics and visualisations, producing two clean, structured datasets for the classification and regression tasks.
  
  Notebook 2 Develops models to classify whether a patient survives or not. Compares Logistic Regression, Naïve Bayes, and K-Nearest Neighbours, then combines them into an ensemble voting classifier. Includes hyperparameter tuning with grid search and cross-validation, and evaluates models with confusion matrices, ROC curves, precision, recall, F1-score, and AUC.
  
  Notebook 3 Predicts patient survival time in months using Decision Tree regressors. Builds both fully grown and pruned trees to balance complexity and interpretability. Compares performance with RMSE, MAE, and R², and visualises regression trees to highlight key predictive factors influencing survival duration.


  This project was completed as part of my second year Machine Learning and Data Mining module in the BSc Data Science and Analytics course at the University of Westminster.


