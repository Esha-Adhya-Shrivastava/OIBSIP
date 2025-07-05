Oasis Infobyte Internship – Task 4

Project: House Price Prediction using Linear Regression

Dataset Used:
- File: `Housing.csv`
- Source: [Kaggle](https://www.kaggle.com/code/ashydv/housing-price-prediction-linear-regression)

Objective:
To build a linear regression model that accurately predicts house prices based on various features such as area, number of rooms, amenities, and furnishing status.

Steps Performed:
- Data loading and inspection
- Checked for missing values
- Categorical data encoding (label & one-hot encoding)
- Feature and target variable separation
- Train-test split
- Trained a linear regression model using `scikit-learn`
- Evaluated the model using MSE, RMSE, and R² Score
- Visualized Actual vs Predicted values
- Exported the trained model using `joblib`

Files Included:
- `House_Price_Prediction.ipynb` — Full Jupyter notebook
- `Housing.csv` — Raw dataset
- `house_price_model.pkl` — Trained linear regression model

Key Insights:
- Achieved an R² score of **~0.65**, explaining 65% of the price variation
- Average prediction error (RMSE) was around ₹13.24 lakhs
- Visualized model accuracy using a scatterplot

Tools & Libraries:
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, Joblib

Outcome:
A functional regression pipeline that estimates housing prices — useful for real estate agencies, investors, or analytics teams.
