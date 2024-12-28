# Stock Price Prediction: Integrating News Sentiment and Technical Indicators
## Overview
This project combines sentiment analysis of news headlines with technical stock indicators to predict stock market movements. By leveraging pre-trained transformer models and advanced machine learning algorithms, the project achieves high accuracy in forecasting stock trends.
## Key Features
- *Sentiment Analysis*:
Fine-tuned BERT and DistilBERT for sentiment prediction (positive/negative) and probability estimation.
- *Prediction Models*: Used Random Forest and LightGBM for stock movement prediction.
- *Dataset*: Merged Nifty50 stock data with daily news summaries.
- *Indicators*: Technical stock attributes: Open, High, Low, Turnover, Shares Traded.
- Sentiment probabilities as an additional feature.
## Workflow
### Web Scraping & Data Preparation:
- Scraped daily news summaries andmerged with Nifty50 stock data..
### Sentiment Analysis:
- Fine-tuned BERT for binary sentiment analysis (1/0).
- Used distill BERT for sentiment prediction(negative/positive) and sentiment probabilties.
### Stock Movement Prediction:
- Integrated sentiment probabilities with stock trading indicators.
- Built and evaluated models using Random Forest and LightGBM.
## Results
### LightGBM Model:
- Accuracy: 72%
- Comprehensive metrics: Precision, Recall, F1-Score.
### Random Forest Model:
- Accuracy: 98.2%
- Robust evaluation through classification reports.
## Tools and Libraries
- Data Handling: pandas, BeautifulSoup
- Machine Learning: scikit-learn, lightgbm
- Sentiment Analysis: transformers (Hugging Face FinBERT & DistilBERT)
- Visualization: Matplotlib
