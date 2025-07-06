# email-spam-ML-model
This project implements a supervised machine learning model to classify emails as spam or not spam (ham). It uses text classification techniques such as Bag of Words (CountVectorizer) and Naive Bayes algorithm, which are well-suited for natural language processing (NLP) tasks like spam detection.

🧠 Model Description
Type: Text Classification

Algorithm Used: Multinomial Naive Bayes

Feature Extraction: CountVectorizer (Bag of Words model)

Evaluation Metrics: Accuracy, Precision, Recall, F1-score

📦 Dataset
Commonly used datasets:

SpamAssassin Public Corpus

Kaggle Spam Classification Dataset

Format: Email/SMS text + label (spam/ham)

Example:

Message	Label
"Congratulations! You've won $1000!"	Spam
"Hi, can we meet today at 4 PM?"	Ham

⚙️ How It Works
Preprocessing:

Lowercasing, punctuation removal, stopword removal, tokenization

Vectorization:

Emails are converted into a matrix of token counts using CountVectorizer.

3
