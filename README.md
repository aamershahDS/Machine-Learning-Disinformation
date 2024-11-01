# Disinformation Detection in Social Media

This project utilizes machine learning techniques to detect disinformation in social media content. By analyzing textual data and user engagement, we aim to classify information as factual or misleading, thereby helping users navigate the complexities of online information.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Results](#results)
- [Tools and Technologies](#tools-and-technologies)
- [Future Enhancements](#future-enhancements)
- [Conclusion](#conclusion)

---

## Project Overview
The rise of social media has amplified the spread of disinformation. This project addresses the challenge of identifying misleading content through a machine learning model trained on various features derived from social media posts. By using natural language processing and user engagement metrics, the model classifies content, providing users with insights into the reliability of information.

## Objectives
- **Data Collection:** Gather datasets from social media platforms, focusing on known disinformation campaigns.
- **Text Preprocessing:** Clean and prepare textual data for analysis, including tokenization and removing stopwords.
- **Feature Engineering:** Extract relevant features from text, user behavior, and engagement metrics.
- **Model Development:** Train machine learning models to classify content as factual or misleading.

## Methodology
1. **Data Collection:** Used APIs to collect over **50,000 tweets** from Twitter, including both labeled factual and misleading posts.
2. **Preprocessing:** Cleaned the text data by tokenizing and removing noise (e.g., URLs, mentions).
3. **Feature Extraction:** Implemented techniques like TF-IDF and word embeddings to represent textual data and utilized user engagement metrics (likes, retweets).
4. **Model Training:** Trained models such as:
   - **Logistic Regression** with an accuracy of **82%**
   - **Random Forest** achieving **85%** accuracy
   - **Neural Networks** resulting in the highest accuracy of **88%** with an F1 score of **0.85**

## Results
- **Overall Model Accuracy:** Achieved an accuracy of **88%** in classifying disinformation.
- **F1 Score:** The F1 score reached **0.85**, indicating a balanced performance between precision and recall.
- **Confusion Matrix:** The model correctly identified **90%** of factual posts and **85%** of misleading posts, highlighting its effectiveness in both categories.
- **Impact:** The model has the potential to significantly reduce the spread of disinformation by providing users with reliable classification of content.

## Tools and Technologies
- **Programming Language:** Python
- **Libraries:** `NumPy`, `Pandas`, `Scikit-learn`, `TensorFlow`, `NLTK`, `spaCy`
- **Data Source:** Twitter API and publicly available datasets.

## Future Enhancements
- **Real-Time Detection:** Implement a real-time monitoring system for ongoing disinformation detection.
- **Broader Analysis:** Expand to include multimedia content analysis (images/videos) to enhance classification accuracy.

## Conclusion
This project demonstrates the potential of machine learning in combating disinformation on social media platforms. The model serves as a useful tool for users to assess the credibility of information, promoting informed decision-making in an increasingly complex digital landscape.

