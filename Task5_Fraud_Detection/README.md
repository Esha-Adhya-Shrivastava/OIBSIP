
Oasis Infobyte Internship – Task 5

Project: Fraud Detection using Machine Learning

Dataset Used:
- File: `creditcard.csv`
- Source: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Objective:
To build a machine learning model that accurately identifies fraudulent transactions using classification techniques. The project focuses on handling imbalanced data and applying effective modeling strategies.

Steps Performed:
- Loaded dataset and explored structure
- Checked for missing values and class distribution
- Visualized class imbalance using bar graph
- Separated features and labels
- Performed train-test split (80-20)
- Trained model using Logistic Regression
- Evaluated using confusion matrix, precision, recall, F1-score
- Exported the final model using `joblib`

Files Included:
- `Fraud_Detection.ipynb` — Full notebook with code and insights
- `creditcard.csv` — Original dataset not included due to size limits
- `fraud_detection_model.pkl` — Trained classification model

Key Insights:
- Class imbalance was significant (492 frauds vs. 284,315 non-frauds)
- Logistic Regression was able to capture meaningful patterns despite imbalance
- Evaluation metrics helped assess real-world performance

Tools & Libraries:
- Python, Pandas, NumPy
- Scikit-learn, Matplotlib, Seaborn
- Joblib

Outcome:
A basic fraud detection system that can be extended to more advanced models like Random Forests, SMOTE sampling, or deep learning for real-time fraud detection in financial systems.
