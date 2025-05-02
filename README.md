# SMS Spam Detection with Naive Bayes
This project demonstrates how to build a spam detection model using the Multinomial Naive Bayes classifier and text vectorization via CountVectorizer. The dataset contains SMS messages labeled as "ham" (non-spam) or "spam".

### Dataset
Filename: spam emails.tsv
Format: Tab-separated with no header

### Columns:

label: 'ham' or 'spam'

#### message: the text content of the SMS

### Data Overview
Total messages: 5572
Ham: 4825
Spam: 747

### Key Takeaways

Model: Multinomial Naive Bayes is fast and effective for text classification.

Features: Bag-of-Words using CountVectorizer with ~7,456 features.

Performance: High accuracy and excellent AUC indicate robust spam detection


