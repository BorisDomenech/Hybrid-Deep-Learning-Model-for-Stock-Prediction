# Hybrid Deep Learning Model for Stock Prediction

This repository features a hybrid deep learning model leveraging LSTM, GRU, and TCNN architectures for stock price prediction. The seed hyperparameters are optimized via Bayesian Optimization. This project is part of a broader initiative to analyze and recommend investment opportunities across a wide range of stocks by integrating stock prices with recent news sentiment.

---

## Project Scope

This model is a component of a larger system designed to evaluate and recommend stock investment opportunities. The broader project integrates:

- **News Sentiment Analysis**: Assessing the impact of recent news on stock movements by analyzing sentiment and its correlation with price fluctuations.
- **Correlation Studies**: Investigating the relationship between news trends and stock price behavior.
- **Comprehensive Stock Analysis**: Building a scalable framework for comparing multiple stocks and suggesting investment opportunities.

---

## Notebook Overview

The attached Jupyter Notebook (`stock_price_predictability_AAPL.ipynb`) showcases:

- A step-by-step implementation of the hybrid deep learning model for predicting stock price movements.
- A case study focused on **AAPL stock**, including:
  - Data preprocessing
  - Model training
  - Performance evaluation
- Visualizations of prediction results and insights into model performance.

---

## Prerequisites and Setup

To run the notebook and replicate the results, ensure you have the following libraries installed:

- Python 3.8+
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Seaborn
