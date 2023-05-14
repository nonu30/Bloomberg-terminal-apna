import yfinance as yf


# Get the user input
symbol = input("Enter the stock symbol: ")

# Get the live price of the stock
price = yf.Ticker(symbol).info['currentPrice']

# Print the live price
print("The live price of {} is {}".format(symbol, price))
