# Machine Learning Engineer Nanodegree
## Project: Cryptocurrency Price Indicator

Proposal: proposal.pdf
Report: report.pdf

Predict daily returns and daily volatility of bitcoin and ethereum, based on historical market and google trends data.

Implemented in python3. Uses the following packages:
- Keras with tensorflow backend (for LSTM models)
- scikit-learn for TimeSeriesSplit and GridSearchCV
- pandas for data structures (DataFrames and Series)
- numpu for numerical analysis
- matplotlib and seaborn for visualization
- pytrends for fetching Google trends data
- datetime for date manipulations

Three ipython notebooks are of relevance for this project:
- Data Preparation, EDA & Feat Eng: Covers the Data preparation, exploration and feature engineering
- Normalization, Benchmarks and training: Covers the benchmarks, LSTM-based training and results. This is to be run after the first notebook
- Cryptos_PsychSignal_Stockwits: Notebook developed in Quantopian platform to retrieve stocktwits sentiment data. Unused for this project, but uploaded here for future reference

