# OIBSIP_WajihaTariq7_Task3
E-mail Spam Detection with Machine Learning. 

Objective: The objective of this project was to build a machine learning-based email spam detector using Python that can automatically classify emails as spam or not spam (ham). The goal was to improve email filtering by identifying unwanted or harmful messages using text analysis and classification algorithms.

Steps Performed:
* Data Collection: Used a labeled email dataset from Kaggle containing spam and ham messages.
* Data Preprocessing: Cleaned the text data by removing punctuation, stopwords, and special characters. Converted text into lowercase for uniformity.
* Feature Extraction: Transformed text data into numerical form using techniques like TF-IDF Vectorization or Count Vectorizer.
* Exploratory Data Analysis (EDA): Analyzed word frequency, spam vs ham distribution, and most common spam words.
* Model Building:
  Trained machine learning models such as:
   * Naive Bayes (commonly used for text classification)
   * Logistic Regression (optional comparison model)
* Model Evaluation:
   Evaluated performance using metrics like:
     * Accuracy
     * Precision
     * Recall
     * F1-score
* Prediction: Tested the trained model on new email messages to classify them as spam or ham.

Tools and Technologies Used:

* Python
* Kaggle Notebook
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn (for ML models and vectorization)
* NLTK (for text preprocessing)

Outcome:
The project successfully built an effective spam detection system that can classify emails with high accuracy. The Naive Bayes model performed particularly well for text classification tasks. This project improved understanding of Natural Language Processing (NLP), text preprocessing, feature extraction, and supervised machine learning techniques.
