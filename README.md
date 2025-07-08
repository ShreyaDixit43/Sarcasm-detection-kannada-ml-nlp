# 🌀 Sarcasm Detection in Kannada using Machine Learning

A machine learning-based system to detect sarcastic sentences in the Kannada language. This project focuses on building a custom pipeline including data preprocessing, feature extraction, and multiple ML models to identify sarcastic tone in native text.

## 🧠 Overview

Sarcasm detection is a challenging task in Natural Language Processing (NLP), especially for low-resource languages like Kannada. This project aims to classify Kannada sentences as sarcastic or not by training various ML models on a cleaned and labeled dataset.
This project is built on a custom dataset of Kannada sentences collected from native speakers to accurately capture the nuance of sarcasm in informal and conversational contexts.

## 📌 Features

- Works on Kannada language text data
- Cleans and preprocesses raw sentences
- Custom stemming and tokenization for Kannada
- Removes stopwords, and unwanted characters
- Uses TF-IDF for feature extraction
- Compares multiple ML models:
  - Logistic Regression
  - Linear SVC
  - SGD Classifier
  - Multinomial Naive Bayes
  - Random Forest
  - XGBoost
- BERT-based deep learning model also explored

## 🗃️ Dataset
The dataset consists of 7,285 Kannada sentences labeled as sarcastic or non-sarcastic, manually collected from native speakers to ensure linguistic and contextual accuracy.
- Custom dataset of Kannada sentences
- Each entry labeled as `sarcastic` or `non-sarcastic`
- Data preprocessing steps include:
  - Unicode normalization
  - punctuation removal
  - Stemming using custom Kannada stemmer
  - Stopword removal (manually curated)

## 🛠 Tech Stack

- Languages: Python
- Libraries:
  - pandas, numpy, re
  - scikit-learn
  - xgboost
  - transformers, torch (for BERT)
- Vectorization: TF-IDF
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score
  
## 📌 Applications

This system can be useful in:

- **Social Media Monitoring**: Detecting sarcastic posts or comments to analyze sentiment more accurately.
- **Customer Feedback Analysis**: Identifying sarcasm in reviews to avoid misinterpretation of user sentiments.
- **Chatbots and Virtual Assistants**: Helping conversational AI better understand sarcastic tone for more human-like interaction.
- **Content Moderation**: Assisting moderation teams in flagging misleading or harmful sarcastic remarks.

## 📌 Challenges

- Limited labeled data in Kannada
- Lack of reliable stemmers and stopword lists
- Word sense disambiguation in sarcastic usage

## 🤝 Contributions

Pull requests are welcome. You can contribute by:
- Improving the Kannada tokenizer/stemmer
- Adding more annotated data
- Experimenting with transformer models

## 📬 Contact

Shreya Dixit  
GitHub: https://github.com/ShreyaDixit43

## 📄 License

This project is open-source and available under the MIT License.
