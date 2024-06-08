# Bitcoin vs Gold
![1](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/45077191-e691-43a7-8151-7177da4146ee)
## DESCRIPTION OF THE BUSINESS PROBLEM
The goal of this project is to provide stakeholders with detailed and efficient analysis regarding the yearly price performance of Gold and Bitcoin to determine which asset will provide a higher return over time.

## DESCRIPTION OF THE DATA
* The first data set for the gold price is a data set from kaggle. This dataset provides the year the price was recorded, the average closing price, the yearly opening price, the highest yearly price, the lowest yearly price, the yearly range price, and the yearly close. https://www.kaggle.com/datasets/yafethtb/gold-price-historical-data-1969-2022?select=gold_price_yearly.csv
* The second dataset for the bitcoin price is from yahoo finance. This data provides the yearly open, the yearly high, the yearly low, the yearly close, the trading volume, and the market cap.
https://finance.yahoo.com/quote/BTC-USD/history?period1=1410912000&period2=1699920000&interval=1mo&filter=history&frequency=1mo&includeAdjustedClose=true

## CONCLUSION
In comparison to gold, the return on investment for Bitcoin is substantially larger. Bitcoin is a very volatile asset however, the price swings upward more than compensate for the large dips that occured in the past. When compared to gold, the return on investment for Bitcoin is substantially larger. Bitcoin is also a much newer asset than gold so it the potential for growth is higher. Gold does not suffer from the large drops in price that bitcoin does, but it also does not benefit from the significant increases in price as well. Gold is a much more stable asset but it will not provide investors with any outsized returns on their investment like Bitcoin will.

## DATA CLEANING PROCESS
* Raw data for the 2 assets was uploaded to google sheets and data was cleaned.
* Raw data for both assets was formatted to only include the open price, lowest price, highest price, and close price for each year of the asset’s price history.
* The column containing the date in the raw data has been formatted to only include the year associated with the chosen price metrics and any unnecessary columns have been deleted.
* The numeric price values have been formatted to be displayed in dollar format and rounded to two decimal places.
* Only data for the years between 2015-2022 is displayed and the rest of the data has been deleted. 
#### - Raw Bitcoin price data
![btc-raw-data](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/c51c29af-d6c8-48c2-9dd0-4087f6c8a49a)
#### - Cleaned Bitcoin price data
![btc-cleaned-data](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/f4d86ebd-753a-4beb-bf9a-477d62c75fa6)
#### - Raw gold price data
![gold-raw-data](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/e2539254-9e78-4e69-84ea-c0b1af9bd7af)
#### - Cleaned gold price data
![gold-cleaned-data](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/c43f118b-ac25-41cf-976d-2b450a29c7aa)

## DATA VISUALIZATION
![btc-price-performance-chart](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/38083594-ed65-4a12-bb79-59ed806d92c7)
![gold-price-performance-chart](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/74870241-4c1f-4959-8c90-ed1a829db7e8)
![percent-return-for-btc-and-gold](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/b80affcc-5b4a-42ba-ac4f-6bc607dbd825)
![conclusion](https://github.com/dwhite256/BTC-vs-Gold-Case-Study/assets/170587320/2e7a1b0f-032a-434d-b0ff-735ac76b3176)




