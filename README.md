# Stock_price_predictions

# Accuracy achieved = 90.32258064516128 %

# Summary of files :
1. new.csv is dataset of stock prices of Apple, Microsoft and Intel.
2. data_processing_round_2.ipynb : This file contains backtesting of above mentioned stocks with RSI, EMA and MACD indicators. Formed a new dataset with these values.
3. model_training_round_2.ipynb : Trained the classifier using the new dataset to optimise indicators.
4. stock_price_round_1.ipynb : contains solution of problem statement of round 1 i.e prediction model of stock prices. Used Prophet in python.

# How this works :
1. Download the data of multiple stocks from Yahoo.
2. Clean & process downloaded data.
3. Backtested strategy on above mentioned 3 stocks.
4. Create labels with input dataset for training
5. Create this dataset for all stocks
6. Train classifiers on this data 
7. Compare scores of accuracy of classifiers
8. Highest score achieved using Random Forest Classifier
