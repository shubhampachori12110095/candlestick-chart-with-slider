## A python code for creating candlestick charts with range slider using bokeh

<img src="./images/screenshot1.png" height=500>

This code is meant to showcase part of workflow specific to technical analysis:
* connecting to a sql database to extract price data for a specific trading instrument, and
* plotting a candlestick chart with a range slider and a tooltip for detailed price info

To ilustrate the functionality I'm using a jupyter notebook and daily OHLC price data for two instruments 
(EURUSD currency pair, and the Apple stock) stored in a sqlite database. Each instrument represents a table in the db.

### Usage:
The script can easily be adopted to plot from csv files, assuming they contain the columns `date`, `open`, `high`,
 `low`, `close`.

Required dependencies:
* 


### Disclaimer:
This project is for education purpose and does not represent financial advice, nor should it be used in trading applications.
