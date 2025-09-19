# 2201CS37_CS502
House Price Prediction

This assignment predicts house prices using Machine Learning techniques. The dataset is preprocessed and analyzed to build models for regression and classification.

The dataset used is Housing.csv, which contains the following features:

Numerical Features: area, bedrooms, bathrooms, stories, parking, price

Categorical Features: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus


Target :

For Linear Regression → price (continuous variable).

For Logistic Regression → high_price (binary: 1 if price > median price, else 0).


Methods Used :

1. Data Preprocessing

Missing value check

Encoding categorical features using OneHotEncoder

Standardizing numerical features with StandardScaler

Using ColumnTransformer + Pipeline for clean preprocessing

2. Linear Regression

Trained a regression model to predict house prices

Evaluated using:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

3. Covariance Analysis

Computed the covariance matrix of numerical features

Visualized correlations & covariance using heatmaps

4. Logistic Regression

Converted regression problem into a classification task (High-price vs Low-price houses)

Trained a Logistic Regression model

Evaluated using:

Accuracy
Confusion Matrix
Classification Report (Precision, Recall, F1-score)


Results : 

- Linear Regression achieved good performance in predicting house prices.

- Covariance Analysis showed strong relationships between price and features like area, bedrooms, and bathrooms.

- Logistic Regression successfully classified houses into high-price vs low-price with high accuracy.


Install dependencies :

pip install -r requirements.txt


Run the Jupyter notebook :

jupyter notebook Assignment_1.ipynb


Dependencies : 
Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter


Install them via :

pip install pandas numpy matplotlib seaborn scikit-learn jupyter
