# SMS Spam Detection with Naive Bayes
This project demonstrates a complete text classification pipeline using Python and popular data science libraries. The goal is to classify SMS messages as spam or ham (not spam) using a multinomial Naive Bayes model and text vectorization.

### Project Structure
- main.ipynb — Jupyter notebook containing the entire pipeline: data preprocessing, feature engineering, model training, and evaluation.

- sms.tsv — Dataset used for training and testing the classifier (make sure this file is present in the working directory).

### Workflow Features
Reading and inspecting a labeled SMS dataset

Text preprocessing using CountVectorizer

Converting text into numerical features (document-term matrix)

Splitting data into training and test sets

Training a Multinomial Naive Bayes classifier

Predicting message labels on unseen data

### Evaluating model performance using:

- Accuracy

- Confusion Matrix

- Predicted Probabilities

- ROC-AUC Score

### Model Performance
Accuracy: 98.85%

ROC-AUC Score: 0.9866

### Dependencies
pip install pandas scikit-learn


