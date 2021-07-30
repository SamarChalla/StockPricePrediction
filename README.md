### In this project, Future price of a stock(TATAMOTORS) has been predicted using Monte Carlo Simulations.
## Monte Carlo Simulations:
Monte Carlo Simulations are used to study forecasting, perform risk or uncertainity analysis and probabilities of different outcomes. The basic idea followed in this project is by assigning multiple values to an uncertain variable to achieve multiple results and then averaging the results to obtain an estimate.

# Process followed: 
### 1.Collected data starting from yahoo finance.
### 2.Calculated std_dev and CAGR to make them influence the fluctuations
### 3.Derived random shocks using CAGR, Std_dev and assumed it to be in a normal distribution [np.random.normal()]. Each is a random walk showing one outcome.
### Performed 10000 trials from today and predicted prices for the next year (for 252 trading days) and calculated average and plotted a histogram to showcase the probabilities of various possible outcomes.

# Results:
According the predicted data, the future price of the stock after 1 year has very less probability of going down from the current price.

# Disclaimer:
The study conducted is for educational purposes and doesn't involve any investment advice as there are many other factors that affects stock prices
