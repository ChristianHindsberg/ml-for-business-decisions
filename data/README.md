# Data

Only `online_shoppers_intention.csv` is in the repo. Download the others into this folder (it is git-ignored).

| File | Used by | Source | License | In repo? |
|---|---|---|---|---|
| `online_shoppers_intention.csv` | `02_kmeans_online_shoppers` | [UCI Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset), Sakar et al., doi:10.24432/C5F88Q | CC BY 4.0 | Yes |
| `baseball.csv` | `03_regression_logistic_baseball` | [Moneyball MLB stats 1962-2012 (Kaggle)](https://www.kaggle.com/datasets/wduckett/moneyball-mlb-stats-19622012): download and save as `baseball.csv` | Not clearly stated, so not redistributed here | No |
| `Airline_Tweets.csv` | `01_airline_tweets_eda` | [Twitter US Airline Sentiment (Kaggle)](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment): download `Tweets.csv` and rename it | CC BY-NC-SA 4.0 | No |
| `waste-classification.zip` | `04_image_classification_waste` | [Waste Classification data (Kaggle)](https://www.kaggle.com/datasets/techsash/waste-classification-data): download the archive and rename it | CC BY-SA 4.0 | No (about 450 MB) |

The trading-strategy notebooks download market data from Yahoo Finance (via `yfinance`) and FRED at run time and cache it under `notebooks/trading_strategy/data/` (git-ignored). Yahoo's terms do not allow that data to be redistributed, so no price data is committed.

The order book notebook downloads FI-2010 (Ntakaris et al., 2018, [Fairdata Etsin](https://etsin.fairdata.fi/dataset/73eb48d7-4dbc-4a10-a52a-da745b47a649)) at run time from the copy in the [DeepLOB repository](https://github.com/zcakhaa/DeepLOB-Deep-Convolutional-Neural-Networks-for-Limit-Order-Books). The raw files are not committed.
