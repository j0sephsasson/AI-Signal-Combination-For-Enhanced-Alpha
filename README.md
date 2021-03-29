# AI-Signal-Combination-For-Enhanced-Alpha
Build a random forest to combine 28 signals for enhanced alpha.

# Motivation
This project was part of Udacity's AI For Trading Nanodegree program

# Technologies Used
Python -- Numpy, SciPy, Pandas, Zipline, Alphalens, Sci-Kit Learn

# How It Works
Compute a multitude of conditional Alpha signals, such as:
-- momentum, mean_reversion, overnight_sentiment
-- market regime features: dispersion, volatility
-- date / time features: day of week/month, fiscal quarter

Combine the factors into one using a RandomForestClassifier