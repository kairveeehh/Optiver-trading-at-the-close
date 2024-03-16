## Optiver Trading at the Close

Within this repository, I've crafted a straightforward LightLGM model aimed at predicting the closing price movements of numerous NASDAQ-listed stocks. Leveraging data extracted from the order book and the closing auction of each stock, this model is tailored specifically for Optiver's Trading at the Close competition.

This was in regard to the kaggle contest (https://www.kaggle.com/competitions/optiver-trading-at-the-close/)

![Optiver Trading at the Close](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/dd735ea6-12be-43eb-aed0-3b10d6863e5d)

### Introduction to Closing Auctions

The Nasdaq Closing Cross auction establishes official closing prices, crucial for investors and analysts. Optiver, a leading electronic market maker, utilizes data from both the order book and the auction to provide competitive prices. In this competition, I developed a model predicting closing price movements for Nasdaq-listed stocks using auction and order book data. 

During a closing auction, orders are accumulated over a predefined period and then matched at a single price determined by the buy and sell demand expressed by auction participants. For Nasdaq's closing auctions, orders are accepted from the start of the trading day, with the state of the auction book published at 3:50 PM ET for a duration of 10 minutes before the market closes at 4 PM ET. At this point, orders are matched instantly at a single price.

### Dataset Overview

Understanding the terminologies presented in the dataset description is crucial for effectively tackling the problem statement. This dataset contains historical data for the daily ten-minute closing auction on the NASDAQ stock exchange. The challenge involves predicting the future price movements of individual stocks relative to the price movement of a synthetic index composed of NASDAQ-listed stocks.

![Dataset Description](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/8cd6281b-e6ce-4925-be18-1ae063679ad6)

### Key Terminologies Explained

Various terms such as order book, auction book, market maker, and Weighted Average Price (WAP) necessitated detailed explanations. While theoretical explanations can be found through various sources, the provided images offer practical insights into the mechanics of trading at the close. Additionally, an image illustrating the use of quartiles for outlier detection has been included.

![Terminology Explanations](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/2d479b6b-70eb-4962-8853-1147fde80fed)

### Evaluation Metrics

![Evaluation Metrics](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/f4a395fb-fead-4cdd-ab6b-94728a997bb2)

### Essential Resources and References

To gain insights into market dynamics and trading principles, I consulted several resources:

1. Market Making:
   - Blogs and articles from QuantInsti and Investopedia.
2. Order Types and Order Books:
   - Comprehensive guides from Investopedia and Schwab.
3. Auction Price Decision Framework:
   - Insights from Investopedia and NYSE documentation.
4. Trading at Close Terminologies:
   - Official documentation from Nasdaq.

For a deeper understanding of stock market operations, I recommend exploring the provided resources and references, along with academic papers on stock market prediction techniques.

### Papers for Reference

- [Stock Market Prediction via Deep Learning Techniques](https://arxiv.org/abs/2212.12717)
- [Stock Market Analysis: A Review and Taxonomy of Prediction Techniques](https://www.mdpi.com/2227-7072/7/2/26)

###Author
Kairvee vaswani 
vkairvee@gmail.com

