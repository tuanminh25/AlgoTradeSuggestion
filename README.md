# Algorithmetic Trade

This project retrives stock data from the IEX Cloud API then applied Quantitative Momentum Investing and Quantitative Value Investing strategies to determine the optimal number of stocks to purchase in the S&P 500 Index Fund, based on a specified budget

**Installing project**

*Given that python and Jupiter Notebook have already been installed*

1. Create an IEX Cloud account if not have one

2. Clone this project using 

*git clone git@github.com:tuanminh25/AlgoTradeSuggestion.git*

3. Go into AlgoTradeSuggestion folder, create a file called "secrety.py" which has the format

IEX_CLOUD_API_TOKEN = *Your own IEX_CLOUD_API_TOKEN*

4. Run line by line jupiter notebook to in every ipynb files to get your suggested stock buys quantity exported in 3 files  

*momentum_strategy.xlsx*

*recommended trades.xlsx*

*value_strategy.xlsx*


where each of the files will correspond to each of the strategy

There are given example output files in the source code
