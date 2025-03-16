# Sentiment Analysis Project

## Overview
This project focuses on **Sentiment Analysis** using various Natural Language Processing (NLP) techniques. The goal is to analyze sentiment from text data and classify it into **positive, negative, or neutral** sentiments. Different techniques such as text preprocessing, stop-word removal, lemmatization, and sentiment scoring.

## Dataset
The dataset used is `https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews`, which consists of customer reviews and corresponding sentiment labels.

## Preprocessing Steps
To clean and prepare the text for analysis, the following preprocessing steps were applied:
1. **Tokenization**: Splitting text into individual words.
2. **Stop Words Removal**: Removing common words that do not add meaning.
3. **Lemmatization**: Converting words to their base form.
4. **Lowercasing**: Standardizing text by converting it to lowercase.
5. **Removing Special Characters**: Cleaning punctuation, numbers, and symbols.

## Sentiment Analysis Models
The following models were used to classify sentiment:
- **TextBlob**: A lexicon-based sentiment analysis model.
- **Vader (Valence Aware Dictionary and sEntiment Reasoner)**: Specialized for short social media texts.

