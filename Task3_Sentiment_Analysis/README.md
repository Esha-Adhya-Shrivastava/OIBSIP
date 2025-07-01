Oasis Infobyte Internship – Task 3

Project: Sentiment Analysis

Dataset Used:
- File: `Twitter_Data.csv`
- Source: Kaggle – [Twitter Sentiment Dataset](https://www.kaggle.com/datasets/saurabhshahane/twitter-sentiment-dataset)

Objective:
To develop a sentiment analysis model that accurately classifies tweets into **Positive**, **Neutral**, or **Negative** sentiments using Natural Language Processing and Machine Learning techniques.

Steps Performed:

- Data loading and cleaning
- Handling missing values
- Text preprocessing using NLTK (stopword removal, lowercasing, punctuation removal)
- Feature extraction using TF-IDF Vectorizer
- Label encoding of sentiment classes
- Train-test split
- Model training using Logistic Regression
- Model evaluation with accuracy score, classification report, and confusion matrix
- Saved model and vectorizer using `joblib`

Files Included:
- `Sentiment_Analysis.ipynb` — Full Jupyter notebook with code and results
- `Twitter_Data.csv` — Dataset used
- `label_encoder.pkl` — Encoded target labels
- `tfidf_vectorizer.pkl` — TF-IDF feature transformer

Key Insights:
- Tweets were successfully classified into 3 sentiment categories
- Achieved meaningful accuracy using Logistic Regression
- Confusion matrix visualized the model’s performance clearly

Tools & Libraries:
- Python, Pandas, NumPy
- NLTK, Scikit-learn
- Matplotlib, Seaborn

Outcome:
A functional sentiment analysis pipeline using traditional NLP methods — useful for analyzing customer feedback, social media trends, and public opinion.


