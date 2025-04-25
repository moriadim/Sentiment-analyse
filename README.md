🧠 Sentiment Analysis on Online Product Reviews
This project aims to predict customer sentiment (positive, neutral, or negative) based on product reviews using machine learning techniques. It's designed to assist e-commerce platforms in understanding customer feedback and improving product offerings.​



🔍 What is Sentiment Analysis?
Sentiment analysis, or opinion mining, involves analyzing textual data to determine the sentiment expressed by the author. It's widely used to assess opinions on:​

Products

Services

Policies

Events​

This analysis helps businesses make informed decisions based on customer feedback.​

🛍 About Customer Product Reviews
Customer reviews are pivotal in online shopping decisions:​

90% of consumers read reviews before purchasing.

88% trust online reviews as much as personal recommendations.​

Analyzing these reviews provides valuable insights into customer satisfaction and product performance.​

🎯 Objective
Target Audience: E-commerce businesses seeking to analyze customer feedback.​

Dataset: Online Product Reviews from Datafiniti​

Rows: 71,044

Columns: 25

Target Variable: reviews.rating (Happy, OK, Unhappy)

Feature: review.text​
GitHub

📦 Dataset Source:
Grammar and Online Product Reviews – data.world

🔄 Workflow


Steps:
Data Loading

Data Preprocessing

Removing punctuations and special characters

Stopword removal

Tokenization

Stemming

Feature Extraction

TF-IDF Vectorization

Model Building

Training Support Vector Machine (SVM) and SGDClassifier models

Evaluation

Assessing model performance using appropriate metrics​
GitHub
+2
GitHub
+2
GitHub
+2
GitHub
GitHub
+3
GitHub
+3
GitHub
+3

☁️ Word Cloud
Visual representation of the most frequent terms in the reviews:​



📐 Feature Extraction
To convert textual data into a format suitable for machine learning models, we use TF-IDF Vectorization:​

TF (Term Frequency): Measures how frequently a term occurs in a document.

IDF (Inverse Document Frequency): Measures how important a term is.​
GitHub
+4
GitHub
+4
GitHub
+4

The TF-IDF score is calculated as:​

TF-IDF = TF * IDF​
GitHub
+7
GitHub
+7
GitHub
+7

This transformation helps in emphasizing important words while reducing the weight of commonly used words.​

🤖 Model Building
We train two models using the TF-IDF features:​

Support Vector Machine (SVM): Effective in high-dimensional spaces.

SGDClassifier: Efficient for large-scale learning.​

Both models are evaluated to determine their accuracy in predicting customer sentiment.​

📊 Results
Performance metrics and evaluation results:​



🙌 Conclusion
This project demonstrates a complete pipeline for sentiment analysis on product reviews, providing insights that can help businesses enhance customer satisfaction and product quality.​

🔗 Connect
Created by @moriadim​

Feel free to fork, star, or follow for updates!
