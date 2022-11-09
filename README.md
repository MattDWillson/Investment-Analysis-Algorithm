# Investment Analysis Tool

This algorithm compares the performance of individual stocks and portfolios across the following areas: volatility, returns, risk, and Sharpe ratios. In this case, we have a the historial performance of two algorithmic trading portfolios, as well as the returns of SOROS FUND MANAGEMENT LLC, PAULSON & CO.INC., TIGER GLOBAL MANAGEMENT LLC, and BERKSHIRE HATHAWAY INC. Additionally, we have Google, Costco and Apple returns, which will be weighted and combined to form a custom portfolio. Also, we have the S&P 500 index returns which will be used as a performance benchmark and the risk free rate for Sharpe ratio calculations.

## Process
- Concatenate data frames to compare performance
- Calculate daily returns using the pct_change function
- Calculate cumulative returns using the cumprod fucntion
- Calculate volatility using the std function 
- Calculate volatility on a rolling basis per month (21 day period) 
- Calculate Sharpe ratios
 
## Cumulative Returns - Without Custom Portfolio
<img width="1054" alt="Screen Shot 2021-08-04 at 1 15 26 PM" src="https://user-images.githubusercontent.com/83780964/128225175-4ba21ef7-b80f-4ecd-bf76-1981aba8e9a5.png">

## Risk Analysis - Without Custom Portfolio
<img width="1068" alt="Screen Shot 2021-08-04 at 1 16 40 PM" src="https://user-images.githubusercontent.com/83780964/128225443-e16e4950-3378-456f-99c1-9000ae39af9e.png">

## 21 Day Rolling Standard Deviation - Without Custom Portfolio
<img width="1072" alt="Screen Shot 2021-08-04 at 1 18 38 PM" src="https://user-images.githubusercontent.com/83780964/128225555-8b64d460-0dac-4b88-8287-58fe8ea821f1.png">

## Sharpe Ratios - Without Custom Portfolio
<img width="360" alt="Screen Shot 2021-08-04 at 1 21 06 PM" src="https://user-images.githubusercontent.com/83780964/128225805-9792ecf2-824d-403e-806c-20e76074db40.png">

## Rolling 21 Day Standard Deviation - Including Custom Portfolio
<img width="1073" alt="Screen Shot 2021-08-04 at 1 23 03 PM" src="https://user-images.githubusercontent.com/83780964/128226063-a04f2739-9ff9-492b-a52a-e8376a8ffbc5.png">

## Sharpe Ratios - Including Custom Portfolio
<img width="348" alt="Screen Shot 2021-08-04 at 1 23 44 PM" src="https://user-images.githubusercontent.com/83780964/128226162-6611b097-41a4-4649-b73f-5c6738dc4332.png">

## Cumulative Returns - Including Custom Portfilio
<img width="1066" alt="Screen Shot 2021-08-04 at 1 24 50 PM" src="https://user-images.githubusercontent.com/83780964/128226252-7e5addc8-c596-4878-8bf8-662b6c76da8e.png">



