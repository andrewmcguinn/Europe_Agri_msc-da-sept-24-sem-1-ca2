# Europe_Agri_msc-da-sept-24-sem-1-ca2

Harnessing Data and Statistics to Drive Innovation and Sustainability in Irish Agriculture
📌 Overview

This project investigates how data science, statistical analysis, and machine learning can be leveraged to support innovation and sustainability within Irish agriculture. The study evaluates the performance of multiple machine learning models across both classification and regression tasks, with a strong emphasis on hyperparameter optimisation, model evaluation, and statistical inference.

The project was completed as part of my MSc in Data Analytics.

🧠 Technologies & Tools

Python

Pandas, NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

Matplotlib / Seaborn

📊 Methodology
Data Preprocessing

The dataset contained imbalanced class distributions, which were addressed using SMOTE (Synthetic Minority Over-sampling Technique) to achieve balanced target classes.

Feature preprocessing and data validation were performed prior to model training.

Machine Learning Models

The following models were implemented and evaluated:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbours (KNN)

Multinomial Naive Bayes

Hyperparameter Optimisation

GridSearchCV was employed to identify optimal hyperparameters for each model.

Cross-validation was used to ensure robust and reliable model performance.

📈 Model Evaluation
Classification Metrics

Model performance was assessed using:

Accuracy

Precision

Recall

Cohen’s Kappa

Results:

Multinomial Naive Bayes achieved a cross-validation accuracy of 0.59

Logistic Regression achieved a cross-validation accuracy of 0.58

Both models demonstrated competitive performance in classification tasks

Regression Metrics

Regression models were evaluated using:

R² score

Residual analysis

Results:

Random Forest achieved an R² score of 0.94

KNN achieved an R² score of 0.88

These models outperformed all other regression approaches

Residual plots were generated to assess model fit and error distribution

📐 Statistical Analysis

Hypothesis testing was conducted to compare agricultural output yields of major European countries against Ireland’s yield

Effect sizes were measured using Cohen’s D

The power of each statistical test was calculated to ensure the reliability of conclusions

📌 Key Insights

Ensemble and distance-based models (Random Forest and KNN) provided the strongest predictive performance for regression tasks

SMOTE significantly improved model performance on imbalanced classification data

Combining machine learning with statistical hypothesis testing enabled both predictive accuracy and interpretability
