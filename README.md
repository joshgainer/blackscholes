# blackscholes
This is a straightforward python notebook showing how we can create a class that allows us to use the Black-Scholes European style options pricing
model. The class has two different methods: one for call pricing and the other for put pricing. 

I updated this repo to directly pull tickers using the yfinance library, and with the historical data from that library I was able to do an actual calculation of historical volatility (therefore, sigma). Next i will try to wrap the new code in a function or put it into the BlackScholes class if it makes sense to do so. 
