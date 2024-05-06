# Crypto Price Predictor
Utilizes data from BTC and ETH to predict whether DOGE will increase or decrease in price on a 5-minute basis

The data for the APIs gets data on BTC, ETH, and DOGE every 5 minutes from the past 5 days. Then, I made a couple of derived trend columns among other data wrangling steps. Ultimately used a RandomForestClassifier to classify the price as going up or down in the next 5 minute interval. Success rates vary on the performance of DOGE in the past 5 days, but they range from 70-85% accuracy. 