# Real-Time Online News Article Classification Using ML & NLP Techniques

## 📌 Project Overview

This project presents a Machine Learning and Natural Language Processing (NLP) based system for automatically classifying online news headlines into predefined categories.

The system performs text preprocessing and feature extraction using TF-IDF, then applies and compares two Machine Learning algorithms — **Naïve Bayes** and **Logistic Regression** — for news classification.

The project is designed to reduce manual effort, improve news organization, and support real-time classification of continuously generated news content.

## 🎯 Objectives

* Automatically classify online news headlines.
* Reduce the manual effort involved in sorting news.
* Apply NLP techniques for processing news text.
* Convert textual data into numerical features using TF-IDF.
* Compare Naïve Bayes and Logistic Regression algorithms.
* Evaluate model performance using classification metrics.
* Provide a scalable approach for handling large volumes of news data.

## 🧠 Technologies Used

* **Programming Language:** Python
* **Machine Learning:** Scikit-learn
* **Natural Language Processing:** NLP
* **Feature Extraction:** TF-IDF
* **Algorithms:** Naïve Bayes, Logistic Regression
* **Database:** SQLite
* **Development Tools:** PyCharm, Visual Studio Code
* **Operating System:** Windows

## ⚙️ System Workflow

1. Collect news headlines from datasets or online sources.
2. Preprocess the text.
3. Perform tokenization and normalization.
4. Remove stop words, punctuation, and special characters.
5. Convert text into numerical features using TF-IDF.
6. Train Machine Learning classification models.
7. Predict the category of the news headline.
8. Compare model performance using evaluation metrics.
9. Display the predicted news category to the user.

## 📚 Modules

### 1. User Interface Module

Allows users to enter or upload news text and displays the classification result.

### 2. Data Collection Module

Collects news articles from datasets or online sources and stores the data for training and testing.

### 3. Pre-Processing Module

Cleans the news text by removing stop words, punctuation, and special characters and performs tokenization and normalization.

### 4. Feature Extraction Module

Converts textual information into numerical features using TF-IDF.

### 5. News Classification Module

Classifies news into categories such as:

* Politics
* Sports
* Business
* Technology

### 6. Result Display Module

Displays the predicted news category and corresponding result.

### 7. Admin Module

Provides functionality for managing datasets and categories and monitoring system performance.

### 8. Model Training & Evaluation Module

Trains the classification models and evaluates their performance using accuracy, precision, recall, and F1-score.

## 🤖 Machine Learning Algorithms

### Naïve Bayes

Naïve Bayes is used as a probabilistic Machine Learning algorithm for text classification. After preprocessing and TF-IDF feature extraction, it calculates the probability of a headline belonging to each category and selects the category with the highest probability.

### Logistic Regression

Logistic Regression is used as a supervised classification algorithm. It learns the relationship between TF-IDF features and news categories and predicts the category using probability scores.

According to the project evaluation, **Logistic Regression performed better than Naïve Bayes** for the implemented news classification task.

## 📊 Evaluation

The models are evaluated using standard classification metrics including:

* Accuracy
* Precision
* Recall
* F1-Score

The project comparison showed better performance from Logistic Regression in terms of accuracy and reliability.

## 🖥️ Application Features

* User registration and login
* Admin login
* User activation by admin
* News headline input
* Automated news classification
* Classification result display
* Dataset and category management
* Model evaluation

## 🔮 Future Enhancements

The project can be further enhanced by:

* Integrating Deep Learning models such as LSTM or BERT.
* Supporting multilingual news classification.
* Implementing real-time streaming using live news feeds.
* Extending classification from headlines to complete news articles.
* Adding user feedback for continuous model improvement.
* Deploying the application on cloud platforms.
* Adding sentiment analysis to understand opinions expressed in news content.

## 📖 Dataset

The project PPT references the **News Category Dataset** available on Kaggle.

## 👨‍💻 Project Team

* Nookala Sai Meghana
* Udumula Durga Prasad
* Vadla Harshitha
* Vemareddy Palli Ramoj Kumar

## 🎓 Academic Project

**Bachelor of Technology in Computer Science Engineering (Data Science)**
Anantha Lakshmi Institute of Technology and Sciences
Affiliated to J.N.T.U. Anantapuram
