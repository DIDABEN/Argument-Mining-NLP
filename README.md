# Argument Mining & NLP

## Overview
This project explores Argument Mining using Natural Language Processing techniques.
The goal is to classify argumentative spans and the relations between them from annotated texts.

This is an academic project developed as part of a Master 2 in Artificial Intelligence.

## Data
- Academic essays corpus
- Medical texts corpus  
Data provided in JSON format with annotated argumentative spans and relations.

## Methodology
- Text cleaning and preprocessing
- Tokenization and TF-IDF vectorization
- Classification using Logistic Regression
- Model evaluation with precision, recall and F1-score

## Models
- Logistic Regression (baseline)
- BERT (experimented, limited by computational resources)
- RoBERTa (pipeline setup, not fully trained)

## Results
- Span classification accuracy: ~80%
- Relation classification accuracy: ~92%
- Main limitations: class imbalance and linear model constraints

## Technologies
Python, scikit-learn, NLP, Hugging Face, Machine Learning

## Author
Lynda Benkerrou
