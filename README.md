# Sentiment Analysis
CSC 761: Advanced AI<br/>
Spring 2024<br/>
Skills: Python, Matplotlib, NumPy, Jupyter
## Overview
This sentiment analysis project utilizes a Random Forest Classifier to categorize text entries from the Emotions Dataset sourced from Kaggle. Each entry is labeled with one of six emotional categories: Sadness, Joy, Love, Anger, Fear, or Surprise. The dataset is characterized by a skewed class distribution, particularly with a predominance of Sadness and Joy.<br/>
To process the text data, I employed Term Frequency Inverse Document Frequency (TF-IDF) encoding, building a vocabulary that includes only words present in at least 0.0025% of the documents and removing stopwords to optimize the model's performance.
