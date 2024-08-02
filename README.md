# 🧑‍💼 Tantikorn Chatavaraha - Data Science Portfolio

Welcome to my data science portfolio! Here, I showcase my projects and expertise in data science. This repository includes detailed descriptions, methodologies, and results of my work when I was an intern at Botnoi Consulting.

# Chatbot Spam Detection

## Overview

The Chatbot Spam Detection project aims to enhance user experience by filtering out spam messages from chat conversations. This project utilizes natural language processing (NLP) techniques and machine learning models to accurately classify messages as spam or not spam. The project is implemented using Google Colab for ease of collaboration and reproducibility.

## Objective

The primary objective of this project is to develop a robust spam detection system that can:
1. Accurately classify chat messages as spam or non-spam.
2. Utilize machine learning models and NLP techniques to preprocess and analyze text data.
3. Evaluate the performance of various models and select the most effective one based on relevant metrics.

## Key Components

1. **Data Collection**: The dataset consists of raw data that includes only the chatbot's data, the user's texts, and the chatbot's response texts.
2. **Data Preprocessing**:
   - Cleaning and tokenizing text data.
   - Feature extraction using methods like TF-IDF.
3. **Model Training**:
   - Experimentation with multiple machine learning algorithms including Logistic Regression, Random Forest, SVM, and Neural Networks.
   - Hyperparameter tuning and model optimization.
4. **Evaluation**:
   - Performance metrics include accuracy, precision, recall, and F1-score.
   - Special focus on precision and recall to minimize false positives and false negatives.

## Methodology

1. **Data Cleaning**: Removal of special characters, lowercasing, and tokenization.
2. **Feature Engineering**: Extraction of features from text data using vectorization techniques.
3. **Model Selection**: Comparison of different models based on cross-validation results.
4. **Evaluation**: Assessment of model performance using a test set and calculation of key metrics.

## Results

The project successfully developed a spam detection model with the following highlights:
- Efficient preprocessing pipeline for text data.
- Accurate classification with minimized false positive and negative rates.
- Insights into model performance and areas for further improvement.

## Insights

- **Text-Based Insights**: The analysis provided deep insights into common characteristics of spam messages, such as repetitive keywords and certain patterns.
- **Model Performance**: Identified the strengths and weaknesses of different machine learning models in handling text classification tasks.

## Challenges & Solutions

- **Class Imbalance**: Implemented techniques like SMOTE to handle imbalanced data.
- **Text Variability**: Addressed the variability in text by utilizing advanced NLP techniques for feature extraction.

## Future Work

- **Model Improvement**: Experiment with advanced neural network architectures for better accuracy.
- **Real-Time Implementation**: Integrate the model into real-time chat applications for live spam detection.

## Acknowledgements

This project was developed using various open-source tools and libraries. Special thanks to the contributors and the community for their valuable resources and support.

## Conclusion

The Chatbot Spam Detection project demonstrates the effective application of machine learning and NLP techniques to improve user interactions by filtering spam content. The insights gained and the methodologies developed can be further refined and expanded for broader applications.
