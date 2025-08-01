# Sentiment-Analysis
Project focuses on sentiment analysis of Twitter data (Sentiment140) using multiple machine learning techniques to classify tweets as positive or negative. The objective is to explore how different preprocessing strategies, feature extraction methods, and models impact classification performance across datasets of varying sizes and distributions.

# Dataset Link for Analysis
Base Dataset: https://www.kaggle.com/datasets/kazanova/sentiment140/data <br>
Test Dataset 1: https://www.kaggle.com/datasets/arun4545/all-in-one-sentiment-dataset <br>
Test Dataset 2: https://www.kaggle.com/datasets/tariqsays/sentiment-dataset-with-1-million-tweets <br>

# Overall Insight
Accuracy improves step-by-step as cleaning becomes more comprehensive and normalized:
Basic cleaning < Basic + Lemmatization < Advanced cleaning < Advanced + Lemmatization.
Key drivers of improvement:
  1. Removing noisy tokens (HTML entities, single letters).
  2. Expanding contractions (improves sentiment polarity).
  3. Lemmatization (reduces feature sparsity).

Recommendation: Use clean_text_advanced + lemmatize_text for final models, as it offers the best trade-off between noise reduction and semantic preservation.

