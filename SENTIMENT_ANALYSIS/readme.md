# Sentiment Analysis Project

This project focuses on sentiment analysis using different machine learning models, including Naive Bayes, Decision Tree, BiLSTM, and BERT with Transformers. It aims to classify the sentiment of text data into positive, negative, or neutral categories. The project provides code implementations, data preprocessing steps, model training, evaluation, and comparison of different models.

## Introduction

Sentiment analysis is a natural language processing task that aims to determine the sentiment expressed in a piece of text. This project explores four different models for sentiment analysis: Naive Bayes, Decision Tree, BiLSTM, and BERT with Transformers. Each model has its own strengths and capabilities, providing insights into the performance of various approaches.

## Dataset

Preprocessed amazon product review data of Gen3EcoDot scrapped entirely from 
amazon.in
Stemmed and Lemmatized using nltk
sentiment labels are generated using TextBlob polarity scores
Dataset contains features
1) reviews
Stemmed and Lemmatized review using nltk
2) divisions
Categorical label generated using polarity score

## Models

The project includes implementations of the following models:

1. Naive Bayes: The `naive_bayes_model.py` script contains the implementation of the Naive Bayes model for sentiment analysis.

2. Decision Tree: The `decision_tree_model.py` script contains the implementation of the Decision Tree model for sentiment analysis.

3. BiLSTM: The `bilstm_model.py` script contains the implementation of the BiLSTM model using TensorFlow/Keras for sentiment analysis.

4. BERT with Transformers: The `bert_model.py` script contains the implementation of the BERT model with Transformers using the Hugging Face library for sentiment analysis.

Each model script provides functions for data preprocessing, model training, and evaluation.

## Evaluation

The evaluation of each model includes metrics such as accuracy, precision, recall, and F1-score. These metrics help assess the performance of the models in sentiment classification.

## Results

The results obtained from the model evaluation are presented in the project documentation [link to documentation]. The results include a comparison of the performance of different models based on the evaluation metrics.

## Future Work

The project has potential for future enhancements and extensions. Some areas for future work include:

- Implementing advanced preprocessing techniques for text data.
- Exploring ensemble methods to combine the predictions of multiple models.
- Conducting more comprehensive hyperparameter tuning for each model.
- Investigating model interpretability techniques, such as attention visualization.
- Expanding sentiment analysis to include other modalities like images or audio.
