# Module 3 Challenge - Bitcoin Exchange Aribtrage Analysis
Module 3 Challenge Repository 

We wanted to to analyze bitcoin closing prices across two different Bitcoin trading platforms to understand if any arbitrage opportunities existed. The 2 exhanges we analyzed are coinbase and bitstamp. We utilized data from January 1st, 2018 to March 31st, 2018 from both exchanges.  If an arbitrage situation presented itself, we wanted to see if we could capitalize on making profitable trades that took into consideration our 1% trading.  Additionally, if we could make profitable trades, how much would our average trade make that day and the cumulative profits for each day.  


---

## Technologies



**Pandas** - Python library that’s designed specifically for data analysis

**Pathlib** - import *Path* from **Pathlib** - provides an object API for working with files and directories.

**%matplotlib inline** - is a magic function in IPython

---

## Installation Guide

Before running the code, please install the following dependencies:

**import** pandas **as** pd

**from** pathlib **import** Path

**%matplotlib inline**

---

## Usage

To run the application, clone the repository and run the crypto_arbitrage.ipynb in Jupyter Lab.  The dates chosen for specific profitable trade dates are January 3rd, 2018, January 14th, 2018, and January 27th, 2018.  

**The below screenshot shows why we focused on these 3 dates in January with the price dislocation growing over the month of Jan:**

![January_2018](Bitstamp_Coinbase_Jan18.png)

**Summary of Profitable Trades for each day:**
![Profitable_Trades_Summary](Profitable_Trade_Summary.png)

**Summary of Cumulative Profits for each trade day:**
![Cumulative_Profits_Summary](Cumulative_Profit_Summary.png)

**Graph of Cumulative Profits for each trade day:**
![Graph_of_Cumulative_Profits](Cumulative_Profit_Graph.png)


---

## Contributors


James C. Willis

SMU Fintech

Scott Slusher


---

## License


Jupyter Lab

Python