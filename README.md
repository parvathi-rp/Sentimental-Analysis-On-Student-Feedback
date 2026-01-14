EDUSENTI – Sentiment Analysis of Student Feedback

EDUSENTI is a machine learning–based sentiment analysis system designed to automatically analyze student feedback across multiple academic dimensions using Natural Language Processing (NLP). The project helps educational institutions extract meaningful insights from unstructured textual feedback and supports data-driven decision making.

🔍 Project Overview

Student feedback is often collected in textual form, making manual analysis time-consuming and subjective. EDUSENTI automates this process by preprocessing feedback text, extracting features using TF-IDF, and applying machine learning models to classify sentiment across multiple categories such as teaching quality, course content, examinations, laboratory work, library facilities, and extracurricular activities.

🛠️ Technologies Used

Python

Pandas – data handling and preprocessing

NLTK – stopword removal and text cleaning

Scikit-learn – TF-IDF, Naïve Bayes, multi-label classification

Joblib – model persistence

Excel (.xlsx) – input and output data storage

⚙️ Features

Text preprocessing (lowercasing, punctuation removal, stopword elimination)

Multi-label sentiment classification using Multinomial Naïve Bayes

Numeric sentiment prediction (Positive: 1, Neutral: 0, Negative: -1)

Model evaluation using classification reports and confusion matrices

Export of predictions to Excel format

Reusable trained models saved using Joblib

📊 Workflow

Load student feedback data from Excel

Preprocess text data

Extract features using TF-IDF

Train multi-output sentiment classification models

Evaluate model performance

Predict sentiment for new feedback

Save results and trained models

📁 Output

Predicted sentiment values for each feedback category

Excel file containing sentiment analysis results

Saved ML models for future use without retraining

🎯 Use Case

This project can be used by educational institutions to:

Analyze large volumes of student feedback efficiently

Identify strengths and weaknesses across academic services

Reduce manual effort and bias in feedback evaluation

🚀 Future Enhancements

Web-based interface for feedback submission

Visualization dashboards for sentiment trends

Integration with databases and real-time feedback systems

Use of advanced deep learning models for improved accuracy
An application that analyses sentimental behaviour based on student feedback.
## Authors
- [Parvathi R P] (https://github.com/parvathi-rp)
- [Sadiya Mariyam] (https://github.com/sadiya-mariyam)
- [Safiya T] (https://github.com/safiya-2007)
