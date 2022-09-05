Install following to run this script:

1. Python
2. Jupyter Notebook


This python script gets the list of Most Actives ticker symbols from the https://money.cnn.com/data/hotstocks/ website and data related to symbols such as open price, volume and pe ratio from https://www.google.com/finance/quote/Symbol:NYSE website.

It also stores the data in stocks.txt(Text file) and StocksDatabase.db(Database file) file.

To check database file(sqlite) online visit: 

https://sqliteonline.com/ 


Details of data which is collected from both websites:
1. Ticker Symb: It is a text value of most actives ticker symbols. For example: F represents symbol for Ford Motor Co.
2. OpenPrice: It is a value of open price of symbol. For example: DAY RANGE value of F is  18.61− 19.49. So, open price of F will be $18.61.
3. Volume: It is the value of volume of symbol. For example: Volume of F is 107.59M which is equivalent to 107590000.
4. P/E Ratio: It is the value of pe ratio of symbol. For example: P/E Ratio of F is 27.27.
