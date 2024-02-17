# The News Trader ReadMe

## Description

The News Trader is a trading robot developed by the Forex Robot Easy Team. It is designed to take advantage of news releases in the forex market. This code provides an example of how the News Trader works and how it can be used to execute trades.

For detailed reviews and trading results of the official News Trader product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/news-trader-review-mastering-xauusd-news-impact/).

## Installation

To use the News Trader code, follow these steps:

1. Download the code file.
2. Open your MetaTrader platform.
3. Go to 'File' -> 'Open Data Folder'.
4. Open the 'MQL4' folder.
5. Open the 'Experts' folder.
6. Copy the code file into the 'Experts' folder.
7. Restart MetaTrader to load the code.

## Usage

To use the News Trader, follow these steps:

1. Set the desired news release time in the `newsReleaseTime` input parameter. The format is `D'yyyy.mm.dd HH:ii:ss'`.
2. Compile the code.
3. Attach the News Trader to a chart in MetaTrader.
4. The News Trader will automatically execute trades based on the defined news release time.

## Important Notes

- This code is provided as a sample and is not the official developer's code for the News Trader product. The official developer can be found using MQL5.
- The News Trader relies on the Trade library and its dependencies. Make sure to include the necessary libraries in your MetaTrader platform.
- The News Trader places a pending order when it's time for the news release. It then modifies the order with take profit and stop loss levels based on the market reaction.

## Disclaimer

ForexRobotEasy is not the official developer of the News Trader product. We only provide a sample code that can work as described in the product. To find the official developer and obtain the official version, please use MQL5.

For detailed reviews and trading results of the official News Trader product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/news-trader-review-mastering-xauusd-news-impact/).
