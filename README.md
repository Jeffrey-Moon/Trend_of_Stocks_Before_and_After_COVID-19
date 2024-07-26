# Stock Sentiment Analysis and Prediction Project

## Overview

This project investigates the trends of major stocks before and after the COVID-19 pandemic. Utilizing artificial intelligence, the project aims to predict stock movements in scenarios similar to a pandemic outbreak. The analysis includes sentiment classification of stock-related comments and the prediction of stock trends using advanced machine learning models.

## Project Structure

- **Data Collection**: Stock data was gathered from various sources, including Yahoo Finance, for companies such as Tesla (TSLA), Google (GOOG), Apple (AAPL), and others.
- **Sentiment Analysis**: Three models were developed to classify stock comments into "positive," "neutral," or "negative":
  - Logistic Regression
  - Long Short-Term Memory (LSTM)
  - Bidirectional Encoder Representations from Transformers (BERT)
- **Trend Analysis and Prediction**: The project also focused on analyzing stock trends during the pandemic and predicting potential outcomes in similar future events.

## Models and Methods

### Logistic Regression
A simple, yet effective model used as a baseline for sentiment classification. The data was vectorized using TF-IDF and classified using Logistic Regression.

### LSTM
An advanced neural network model capable of capturing sequential dependencies in data. The LSTM was trained using word embeddings to classify the sentiment of stock-related comments.

### BERT
A state-of-the-art transformer model fine-tuned for the sentiment classification task. BERT's ability to understand contextual information makes it highly effective for this application.

## Evaluation

The models were evaluated using standard metrics like accuracy, precision, recall, and F1-score. Cross-validation was used to ensure the robustness of the results. The performance of each model was compared, and the best-performing model was selected for deployment.

## Usage

1. **Data Preprocessing**: Clean and preprocess the stock data.
2. **Model Training**: Train the Logistic Regression, LSTM, and BERT models on the processed data.
3. **Evaluation and Comparison**: Evaluate the models and select the best-performing one.
4. **Prediction**: Use the selected model to predict stock movements during scenarios like the COVID-19 pandemic.

## Future Work

- Enhancing the model's accuracy by incorporating more features and data.
- Extending the analysis to include additional economic indicators.
- Developing a user-friendly interface for real-time sentiment analysis and prediction.

## License

This project is licensed under the MIT License.
