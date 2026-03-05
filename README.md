# NLP-Based-Spam-Detection-using-TF-IDF-and-Naive-Bayes


📧 Spam SMS Classification using Machine Learning

This project is a Machine Learning-based text classification system that detects whether a message is Spam or Ham (Not Spam). The model is trained using Natural Language Processing (NLP) techniques and probabilistic classification algorithms.

🚀 Project Overview

The goal of this project is to build a robust spam detection system that can automatically classify emails or SMS messages into:

✅ Ham (Legitimate Message)

🚫 Spam (Unwanted / Fraudulent Message)

The system uses text preprocessing, feature extraction, and supervised machine learning algorithms to achieve high classification performance.

🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

NLTK

Matplotlib / Seaborn (for visualization)

📂 Project Workflow
1️⃣ Data Preprocessing

Removed special characters and punctuation

Converted text to lowercase

Removed stopwords

Applied stemming / lemmatization

2️⃣ Feature Engineering

Used Bag of Words (BoW)

Used TF-IDF Vectorization

Converted text into numerical feature vectors

3️⃣ Model Building

Trained Naive Bayes Classifier

Also experimented with Logistic Regression

Compared model performance

4️⃣ Model Evaluation

Accuracy Score

Precision & Recall

Confusion Matrix

ROC-AUC Score

📊 Results

Achieved high recall for spam detection

Optimized model to reduce false negatives

Successfully classified real-world sample SMS and emails

💡 Key Learnings

Text preprocessing significantly impacts model performance

TF-IDF performs better than simple Bag of Words in most cases

Naive Bayes works well for text classification problems

🔮 Future Improvements

Deploy model using Flask / FastAPI

Add real-time email filtering system

Improve detection of phishing-style spam
