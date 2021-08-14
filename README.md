# Investment Analysis Tool
The algorithm is meant to allow investment managers to analyze and compare portfolio performance across multiple metrics: volatility, returns, risk, and Sharpe ratios. The process involved fetching historical performance for multiple portfolios and a custom portfolio comprised of ESG stocks (Apple, Google, and Costco). The next step required converting csv files into pandas data frames whcih allows the user to conduct a perforrmance analysis using the built in time series features of pandas. Ultimatley the algorithm determined that algorithmic trading strategies outperformed all other portfolios including whale investors, hedge funds, mutual funds, and a custom portfolio comprised of Apple, Costco, and Google. Tools / Languages: JupyterLab, Python, Pandas, matplotlib 

## Process
- Concatenate data frames to compare performance
- Calculate daily returns using the pct_change function
- Calculate cumulative returns using the cumprod fucntion
- Calculate volatility using the std function 
- Calculate volatility on a rolling basis per month (21 day period) 
- Calculate correlation matrix
- Calculate Sharpe ratios
- 
## Cumulative Returns - Without Custom Portfolio
<img width="1054" alt="Screen Shot 2021-08-04 at 1 15 26 PM" src="https://user-images.githubusercontent.com/83780964/128225175-4ba21ef7-b80f-4ecd-bf76-1981aba8e9a5.png">

## Risk Analysis - Without Custom Portfolio
<img width="1068" alt="Screen Shot 2021-08-04 at 1 16 40 PM" src="https://user-images.githubusercontent.com/83780964/128225443-e16e4950-3378-456f-99c1-9000ae39af9e.png">

## 21 Day Rolling Standard Deviation - Without Custom Portfolio
<img width="1072" alt="Screen Shot 2021-08-04 at 1 18 38 PM" src="https://user-images.githubusercontent.com/83780964/128225555-8b64d460-0dac-4b88-8287-58fe8ea821f1.png">

## Correlation Matrix - Without Custom Portfolio
<img width="1076" alt="Screen Shot 2021-08-04 at 1 19 50 PM" src="https://user-images.githubusercontent.com/83780964/128225664-901a76f3-3b07-4682-9903-8257116dcc61.png">

## Sharpe Ratios - Without Custom Portfolio
<img width="360" alt="Screen Shot 2021-08-04 at 1 21 06 PM" src="https://user-images.githubusercontent.com/83780964/128225805-9792ecf2-824d-403e-806c-20e76074db40.png">

## Rolling 21 Day Standard Deviation - Including Custom Portfolio
<img width="1073" alt="Screen Shot 2021-08-04 at 1 23 03 PM" src="https://user-images.githubusercontent.com/83780964/128226063-a04f2739-9ff9-492b-a52a-e8376a8ffbc5.png">

## Sharpe Ratios - Including Custom Portfolio
<img width="348" alt="Screen Shot 2021-08-04 at 1 23 44 PM" src="https://user-images.githubusercontent.com/83780964/128226162-6611b097-41a4-4649-b73f-5c6738dc4332.png">

## Cumulative Returns - Including Custom Portfilio
<img width="1066" alt="Screen Shot 2021-08-04 at 1 24 50 PM" src="https://user-images.githubusercontent.com/83780964/128226252-7e5addc8-c596-4878-8bf8-662b6c76da8e.png">



