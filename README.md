# Stock-Price-Prediction-Using-Sentiment-Analysis

## Overview
This project explores the exciting intersection of **financial markets** and **natural language processing (NLP)** by predicting stock prices using **sentiment analysis**. The goal is to enhance traditional stock price forecasting models by incorporating **public sentiment** from news headlines and social media posts. By analyzing Tesla's stock prices alongside sentiment data, we aim to uncover how market emotions influence stock Prices.

Financial markets are volatile, and stock prices are driven not just by numbers but also by **investor sentiment**. This project integrates sentiment analysis into **time-series forecasting models** to capture both numerical trends and qualitative market signals.

![My Remote Image](https://media.istockphoto.com/id/1213159713/photo/big-data-technology-for-business-finance-concept.jpg?s=1024x1024&w=is&k=20&c=XqsX7eWf-LItwYuJfZ152iX6OnbxuLWRSNbSjrKCz5A=)

## Models Used
To achieve accurate stock price predictions, we implemented three machine learning models, each offering unique strengths:

### 1. **Linear Regression**
A fundamental statistical model that assumes a linear relationship between input features and the target variable. In this project, Linear Regression provided a **baseline prediction** and proved to be effective for capturing general trends in the stock price data.

- **Strength**: Simple and interpretable.
- **Limitation**: May not capture complex patterns in data.

### 2. **XGBoost**
An **ensemble learning method** based on decision trees, XGBoost is known for its accuracy and speed in handling large datasets. In this project, XGBoost excelled at identifying **non-linear relationships** between sentiment data and stock prices.

- **Strength**: Highly flexible and can handle missing data.
- **Limitation**: Requires careful hyperparameter tuning.

### 3. **Long Short-Term Memory (LSTM)**
A **deep learning model** designed for **time-series forecasting**, LSTM networks are well-suited for capturing long-term dependencies in sequential data. In this project, LSTM was used to predict future stock prices by learning patterns from historical price data and sentiment scores.

- **Strength**: Can capture long-term dependencies in sequential data.
- **Limitation**: Computationally intensive and requires significant data preprocessing.

## Sentiment Analysis Using Pretrained Model
For sentiment analysis, we used a **pretrained BERT-based model** to extract sentiment scores from financial news and social media posts. This model can identify whether the sentiment expressed in text is **positive**, **negative**, or **neutral**. The sentiment scores were then used as additional features in our stock price prediction models.

- **Pretrained Model**: `FinBERT` (optimized for financial text).

## Key Features
- **Historical Stock Data**: Tesla's stock prices sourced from Yahoo Finance.
- **Sentiment Data**: Extracted from tweets and news articles.
- **Integrated Sentiment Scores**: Used to enhance traditional predictive models.

## Conclusion
By integrating sentiment analysis into stock price prediction, this project demonstrates that **market emotions** can provide valuable insights into financial forecasting. The combination of Linear Regression, XGBoost, and LSTM models allows for a robust comparative analysis of traditional and advanced predictive techniques.

