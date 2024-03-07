# Module_11
### This was completed with the support of: Pablo, Shah, and the TA. 
#### The code takes in Mercado Libre's Search Trend Results and Cross-References it's closing price. The goal is to figure out if Mercado Libre's stock price is influenced by searches online - which we used the Google Trends data. 

#### Steps: 
1) Import key packages into the program: !pip install pystan
 - !pip install prophet
 - !pip install hvplot
 - !pip install holoviews

2) Parse 'google hourly search trends csv'
3) Plot the search trends using .loc function via HVPLOT
4) Calculate median monthly search trend value
5) Plot a heatmap showing day of week and hour of day search trends
6) Plot search over the 52 weeks of the year to see when it's least and most popular
7) Plot the close price, and concat the search trends history and close price
8) Create 3 new columns: Lagged Search Trends, Stock Volatility, and Hourly Stock Returns
9) Prepped data for Prophet()
10) Plotted the data using the Prophet Function
11) Plotted only the yhat_lower yhat_upper and yhat values for my forecast 2000 hours. 


