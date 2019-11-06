# Foreign Exchange Futures Converter
The global foreign exchange market accounts for over $5 trillion U.S. dollars worth of average daily trading volume, making it the largest market in the world.  Within this market, there is a growing class of derivative securities: foreign exchange futures.  It is quite common to access the spot and forward markets for better liquidity when trading futures, but this requires the simultaneous conversion of price and contract size from futures into spot or vice versa.

The primary goal of this project is to allow users to efficiently and accurately price foreign exchange futures given a forward rate and contract size.
## Using the Foreign Exchange Futures Converter
Choose a product.  In this example BRL is selected which represents BRL against USD.

<img src="images/Screen Shot 2019-11-05 at 8.00.26 PM.png" width="225" height="40">


Enter contract size labeled as futures amount.

<img src="images/Screen Shot 2019-11-05 at 8.28.21 PM.png" width="225" height="75">


There will be a corresponding output in currency amount (BRL) and USD amount.

<img src="images/Screen Shot 2019-11-05 at 9.27.27 PM.png" width="300" height="70">


Enter an outright spread that reflects the amount and the current market conditions.  This spread will remain constant between the outright bid and offer price.

<img src="images/Screen Shot 2019-11-05 at 10.19.49 PM.png" width="500" height="70">


Once all the above is input, only the bid on the outright will need to be updated with changes in price.  The futures price and futures spread will automatically update.

<img src="images/Screen Shot 2019-11-05 at 10.37.05 PM.png" width="500" height="165">


With an increase in the outright price, futures is inversely affected.

<img src="images/Screen Shot 2019-11-05 at 10.37.51 PM.png" width="500" height="165">


## Links
* Futures Specifications: [CME Group](https://www.cmegroup.com/trading/fx/)
