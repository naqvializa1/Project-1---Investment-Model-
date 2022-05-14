# Project-1---Active-

Prezi: https://prezi.com/p/edit/ysu92emscofq/


**Overview**

This research exercise was done in order to understand if we could create an model to build an investment portfolio that outperforms the S&P Broad Crypto Digital Market Index. Due to the expansive nature and sheer *large/massive* number of investable assets in the Crypto space, it can get quite complex, since there are many variables that need to be taken into account when investing. Our model and future platform, provide a safe option for investors to gain exposure to these markets while **outperforming the *Main market index*/SPCBDM ? **

Our idea was to understand if a combination of 2 sets of Crypto Assets produced better returns than just 1 set of Coins/Assets, without drastically increasing volatility and skewing the Risk profile of the portfolio.

In addition to the old/famous/veteran coins that most people have heard of in the Cryptocurrency space, we wanted to see if Analyzing protocols in a rapidly growing DeFi sector provided some insights/value and improved our potential returns. DeFi is a rapidly growing sector within the CryptoCurrency space that has grown from about 500Million to 150Billion in 2 years. The crypto market as a whole has been in a downtrend for the better part of the last year and we wanted to see the effect of including some variety of undervalued coins into our portfolio and see what **findings we found??** (This last line needs to be changed/edited lol)  
_______________________________________________________________________________________________________________________________________________________________________

**Technologies**

Our model utilizes Python (v 3.1.0) and the following libaries: 

1. pandas 
2. numpy
3. pickle
4. os
5. MCForecastTools
6. pathlib
7. requests
8. json
9. defillama
10. dotenv
11. pandas_datareadr
12. datetime
13. plotly
14. seaborn
15. matplotlib
16. hvplot 
______________________________________________________________________________________________________________________________________________________________________

**Installation Guide**

Most of the libraries listed above were part of the base applications that were installed with the Python version listed above; However, there were some individual packages and API's that needed to be installed. One can reference the Pip Package Installation Website for further support:
https://packaging.python.org/en/latest/tutorials/installing-packages/#ensure-you-can-run-python-from-the-command-line
_______________________________________________________________________________________________________________________________________________________________________
**Application of the Model: **

Research: 
The first step of this process was to ensure that we utilized the relevant API's to provide us with our pricing information for the different cryptocurrencies. We used 3 API's throughout the research process: 
  1. CoinMarketCap API: To access the coins for Coinset A (Veteran Coins)
  2. DefiLlama API: To access the coins for Coinset B (DeFi Sector Coins)
  3. Yahoo Finance API: To access the historical data for both Coinsets as well as the data for the SPCBDM Index.

Data Cleaning: Sorting out the Datasets to fit our filtering criteria and excluding all coins that do not fit the predefined parameters.

Coinset A (Veteran Coins) Parameters: 
1. Market Cap > $15 Billion
2. Time in the market > 4 years --> 01.01.2018

Coinset B (DeFi Coins) Parameters:
1. Total Value Locked > $7 Billion
2. Market Cap > $4.5 Billion

For Coinset B: Further Calculations of Market Cap /Total Value Locked and Fully Dilluted Value / Total Value Locked to understand which coins were undervalued.

Analysis: 

We conducted analysis for Coinset A (Veteran Coins), Coinset B (DeFi Coins) & Coinset C (Combo of A + B) while comparing them to the SPCBDM Index 

- Daily Returns
- Cumulative Returns 
- Sharpe Ratio
- Standard Deviation
- Correlation
- BackTesting
- MonteCarlo Simulation











_______________________________________________________________________________________________________________________________________________________________________
**Contributors & Duties: **

Aarchit Malhotra:  
Aliza Naqvi: 
David Paquiot:
Donte Thrasher:
Kfir Bar: 
_______________________________________________________________________________________________________________________________________________________________________

**Licenses: **

No licenses were used for this project



