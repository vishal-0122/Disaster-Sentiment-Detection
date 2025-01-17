Disaster Sentiment Detection: Tweet Sentiment Classification

Project Overview: This project aims to classify disaster-related tweets into positive (1) or negative (0) sentiments using machine learning models. The dataset contains around 7,000 tweets with sentiment labels, providing a platform for learning and applying text preprocessing and classification techniques.

Objectives: Preprocess tweet data for sentiment classification. Build and evaluate machine learning models for text classification. Identify the model with the best accuracy for the given task.

Methodology:

1. **Data Preprocessing**:
   - Handle null values.
   - Tokenize and clean text (lowercasing, punctuation removal, stopword removal, stemming/lemmatization).
   
2. **Feature Extraction**:
   - Transform text into numerical vectors using Count Vectorizer or TF-IDF.

3. **Model Training**:
   - Train and test the following models:
     - Multinomial Naive Bayes
     - Logistic Regression
     - K-Nearest Neighbors (KNN)

4. **Evaluation**:
   - Use confusion matrix and classification report to compare model performance.


Results: The project identifies the best-performing model based on accuracy, providing insights into effective methods for disaster tweet sentiment analysis.
