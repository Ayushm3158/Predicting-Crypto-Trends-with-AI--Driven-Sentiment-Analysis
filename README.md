# Predicting-Crypto-Trends-with-AI--Driven-Sentiment-Analysis
Predicting Crypto Trends with AI-Driven Sentiment Analysis

Introduction:-
This project explores how sentiment from Twitter influences cryptocurrency price trends, using NLP models for sentiment scoring and machine learning models for correlation and prediction.

Dataset Used:-
Kaggle Dataset: Top 10 Cryptocurrencies Historical Data
Twitter Data: Collected using Tweepy (filtered by cryptocurrency-related hashtags).

Methodology:-
Data Collection: Fetch historical price data from Kaggle and real-time tweets using Tweepy.
Sentiment Analysis: Process tweets using Vader & BERT to assign sentiment scores.
Data Integration: Merge sentiment scores with historical price data for correlation analysis.
Model Training: Train Random Forest Regression, XGBoost, and LSTMs to predict price trends.
Evaluation & Insights: Use correlation coefficients, RMSE, and visualization to assess accuracy.

Results:-
Strong correlation between sentiment and short-term price volatility.
Machine learning models improve predictive accuracy when sentiment is included as a feature.

Future Enhancements:-
Live deployment for real-time sentiment tracking and trading insights.
Incorporate more data sources (Reddit, news, financial reports) for improved accuracy.
