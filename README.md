# Stock_price_predictions

# Accuracy achieved = 90.32258064516128 %

# Summary of files :
1. stock_price_round_2.ipynb contains solution of 1st problem statement i.e prediction model of stock prices.
2. new.csv is dataset of stock prices of Apple, Microsoft and Intel.
3. data_processing_round_2.ipynb : This file contains backtesting of above mentioned stocks with RSI, EMA and MACD indicators. Formed a new dataset with these values.
4. model_training_round_2.ipynb : Trained the classifier using the new dataset to optimise indicators.

# How this works :
1. Download the data of multiple stocks from Yahoo.
2. Clean & process downloaded data.
3. Backtested strategy on above mentioned 3 stocks.
4. Create labels with input dataset for training
5. Backtest & Create this dataset for all stocks
6. Train classifiers on this data 
7. Compare scores
8. Highest score achieved using Random Forest Classifier
