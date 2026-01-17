<h1>Fake News Detection Using Machine Learning</h1>

<img width="1536" height="1018" alt="dashboard" src="https://github.com/user-attachments/assets/616cd14b-dbb6-4ee2-87b6-c323bf18acf5" />

Summary: 

A machine learning project that classifies news articles as Fake or Real using NLP techniques and supervised learning models.

🔍 Overview

This project focuses on building an automated system that analyzes news text and predicts whether the news is fake or genuine using Natural Language Processing (NLP) and machine learning algorithms.


📊 Dataset

Source: <a href="https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification">Fake News dataset (CSV format)</a>

Features Used:

text – News article content

label – Fake or Real

Preprocessing includes: Removing punctuation and special characters, Lowercasing text, Stopword removal, Vectorization using TF-IDF

👉Tools & Technologies

Programming Language: Python 🐍

Libraries: NumPy, Pandas, NLTK, Scikit-learn, Matplotlib / Seaborn, Environment: Jupyter Notebook

⚙️ Methods / Approach

 Data Loading and Exploration

 Text Cleaning & Preprocessing

 Feature Extraction using TF-IDF Vectorizer

 Train-Test Split (80% Training, 20% Testing)

 Model Training (Logistic Regression / Naive Bayes)

👉 Model Evaluation using:

Accuracy Score

Confusion Matrix

Classification Report

👉 Key Insights

TF-IDF significantly improves model performance by capturing important word patterns

Logistic Regression performs well for binary text classification

Proper text preprocessing directly impacts accuracy

📊 Dashboard / Model Output

Confusion Matrix visualization

Accuracy score displayed

Prediction results for sample news text

<img width="1536" height="1018" alt="dashboard" src="https://github.com/user-attachments/assets/1961c1f9-9e29-46bb-8982-5e282df7648c" />



✅ Results & Conclusion

The trained model achieves high accuracy on the test dataset

Successfully classifies news articles as Fake or Real

Demonstrates the effectiveness of NLP + ML for text classification problems

This project proves that machine learning can be a powerful tool in combating misinformation.

🔮 Future Work

Use deep learning models (LSTM, BERT)

Deploy as a web application using Flask or Streamlit

Improve dataset diversity for better generalization

Add real-time news scraping

👤 Author & Contact

Rajan Kumar
🎓 BCA Final Year Student

💻 Skills: Python, Machine Learning, NLP

📧 Email: rajankumarmu1439@gmail.com

🔗 LinkedIn: https://linkedin.com/in/rajan-kumar-mu1439
