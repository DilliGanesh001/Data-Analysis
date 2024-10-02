# Sentiment Analysis using mood_data.txt

## Table of Contents
- Introduction
- Objectives
- Dataset
- Methodology
- Results
- Conclusion

## Introduction
This project involves sentiment analysis using the **mood_data.txt** dataset. The goal is to analyze sentiments expressed in textual data and classify them into positive, negative, or neutral sentiments, providing insights into overall sentiment trends.

## Objectives
- Perform sentiment analysis on textual data.
- Classify sentiments into predefined categories (positive, negative, neutral).
- Analyze sentiment characteristics such as polarity and subjectivity.

## Dataset
The dataset used for this analysis is **mood_data.txt**, which contains textual data labeled with sentiments. Key features in the dataset include:
- **Cleaned_text**: The text after preprocessing (removing punctuation, stop words, etc.).
- **Processed_feature**: Features extracted from the cleaned text, ready for analysis.
- **Polarity**: A numerical representation of sentiment, indicating positivity or negativity.
- **Subjectivity**: A measure of how subjective or objective the text is, usually ranging from 0 (objective) to 1 (subjective).
- **Polarity_encode**: Categorical encoding of the polarity values for classification.

## Methodology
The analysis involves the following steps:
1. **Data Cleaning**: Preprocessing the text to remove unwanted characters and normalize it.
2. **Feature Extraction**: Generating features from the cleaned text for analysis.
3. **Sentiment Analysis**: Calculating polarity and subjectivity for each entry in the dataset using Natural Language Processing (NLP) techniques.
4. **Encoding**: Converting polarity values into categorical labels for classification.
5. **Machine Learning Models**: Implementing the following algorithms for sentiment classification:
   - **Multinomial Naive Bayes (Multinomial_NB)**
   - **Random Forest (Gini)**
   - **Random Forest (Entropy)**
   - **Support Vector Machine (SVM)**
6. **Evaluation**: Assessing the performance of the sentiment analysis models using metrics like accuracy, precision, recall, and F1 score.

## Results
Key findings from the sentiment analysis include:
- Distribution of sentiments (positive, negative, neutral) across the dataset.
- Performance metrics for each machine learning model used, indicating their effectiveness in sentiment classification.
- Insights into the most frequently used words associated with each sentiment category.

## Conclusion
The sentiment analysis effectively classified the textual data into various sentiment categories, providing valuable insights into sentiment trends. Random Forest and SVM demonstrated high accuracy, suggesting their potential for similar applications. Future work could involve implementing advanced models, such as deep learning, to enhance accuracy.
