🐦 Twitter Sentiment Analysis using Machine Learning (NLP)
This project performs sentiment analysis on real Twitter data using Natural Language Processing (NLP) and Machine Learning. It classifies tweets as positive or negative, helping to analyze public sentiment at scale.

📌 Features
🔄 Loads real-world Twitter data from the Sentiment140 Kaggle dataset

🧹 Cleans and preprocesses tweet text (lowercasing, stopword removal, stemming, etc.)

📊 Transforms text into features using TF-IDF vectorization

🤖 Trains a Logistic Regression model to predict tweet sentiment

📈 Evaluates model accuracy (Train: 79.9%, Test: 77.6%)

💾 Saves the trained model for future predictions

🧠 Technologies Used
Python 3.11

pandas, numpy

nltk (Natural Language Toolkit)

scikit-learn (TF-IDF, ML models)

pickle (for model serialization)

Kaggle API (for dataset access)
