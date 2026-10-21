# Sentiment Analysis on Flipkart Product Reviews

A machine learning project that reads a product review and predicts if the customer is Happy (positive) or Unhappy (negative).

## Dataset
About 205,000 Flipkart reviews from Kaggle (Flipkart Product Reviews by Nirali Vaghani). Neutral reviews were removed.

## Tools
Python, Pandas, Scikit-learn, Google Colab

## Method
1. Cleaned the data and removed neutral reviews
2. Converted text to numbers using TF-IDF (single words and word pairs)
3. Split the data: 80% training, 20% testing
4. Trained a Logistic Regression model with balanced class weights

## Results
- Accuracy: about 89%
- Recall for negative reviews: 94%

## What I learned
My first model had 95.7% accuracy but missed many negative reviews because the data had more positive ones. Using balanced class weights and word pairs (like "not good") fixed this.
