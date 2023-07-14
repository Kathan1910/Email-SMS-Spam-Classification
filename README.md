# SMS/Email Spam Classifier

This project aims to develop a machine learning model that classifies SMS and email messages as either spam or not spam.

## Problem Statement

The goal of the SMS/Email Spam Classifier project is to build a machine learning model that accurately classifies incoming messages as spam or not spam, helping users filter out unwanted and potentially harmful content.

## Architecture of the Project

The project follows the following steps:

## 1. Data Cleaning

- **Rename Columns (Text, Target):** Renames the columns of the dataset to "Text" and "Target" for better clarity.
- **Label Encoding on Target Column:** Converts the target labels into numeric values for model training.
- **Check Missing Values:** Identifies and handles missing values in the dataset.
- **Check Duplicate Records:** Identifies and removes duplicate records from the dataset.

## 2. Exploratory Data Analysis (EDA)

Conducts exploratory data analysis to gain insights into the dataset and its characteristics.

## 3. Feature Extraction from Existing Features

Extracts relevant features from the existing dataset to improve the classification model's performance.

## 4. Data Preprocessing

Preprocesses the text data to prepare it for model training:

- **Lower Case:** Converts all text to lower case for consistency.
- **Tokenization:** Splits the text into individual tokens.
- **Handle Special Characters:** Removes or handles special characters in the text.
- **Handle Stop Words & Punctuation:** Removes stop words and punctuation marks from the text.
- **Stemming:** Applies stemming to reduce words to their base form.

## 5. Text Vectorization

Converts the preprocessed text data into numerical vectors for model training:

- **Bag of Words:** Represents the text data as a matrix of word counts.
- **TF-IDF:** Represents the text data as a matrix of TF-IDF (Term Frequency-Inverse Document Frequency) values.
- **Bag of N-Grams:** Represents the text data as a matrix of word n-gram counts.
- **Word2Vec Word Embeddings:** Represents the text data using Word2Vec word embeddings.

## 6. Model Training

Trains the following classification models on the preprocessed and vectorized data:

- **Logistic Regression**
- **Support Vector Classifier**
- **Multinomial Naive Bayes**
- **Decision Tree Classifier**
- **K-Nearest Neighbors Classifier**
- **Random Forest Classifier**
- **AdaBoost Classifier**
- **Bagging Classifier**
- **Extra Trees Classifier**
- **Gradient Boosting Classifier**
- **XGBoost Classifier**

## 7. Ensemble Method

Utilizes ensemble methods to improve model performance:

- **Voting Classifier**
- **Stacking Classifier**

## Query Definitions

- **Spam Message:** A spam message refers to unsolicited and unwanted messages, typically sent in bulk, with commercial or malicious intent.

- **Non-Spam Message:** A non-spam message refers to legitimate and desired messages that are not considered spam.

## Usage

1. Prepare your dataset of SMS and email messages in the desired format (e.g., CSV, Excel).
2. Execute the data cleaning steps mentioned above.
3. Perform exploratory data analysis using the provided Jupyter Notebook.
4. Extract relevant features from the dataset.
5. Preprocess the textual data as described above.
6. Apply text vectorization techniques to convert the text into numerical representations.
7. Train the classification models on the preprocessed and vectorized data.
8. Utilize ensemble methods to improve model performance.
9. Use the provided web app to make predictions on new SMS and email messages.
