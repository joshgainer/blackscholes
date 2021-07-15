# blackscholes
This is a straightforward python notebook showing how we can create a class that allows us to use the Black-Scholes European style options pricing
model. The class has two different methods: one for call pricing and the other for put pricing. 

I updated this repo to directly pull tickers using the yfinance library, and with the historical data from that library I was able to do an actual calculation of historical volatility (therefore, sigma). 

I added some functions that allow for calculating the greeks for the contract very quickly. I'll go back and make it more "general" later by wrapping it all in a class so it can be used for different underlyings.
