# optimal-portfolio-construction

## Objective:

To determine Overpriced and Underpriced Stocks in NSE top 100 companies and constructing a optimal Markowitz portfolio.

## Approach:

- Time series characteristics of both stock price and its returns were analyzed. 
- Plotted **Security Market Line (SML)** to classify stocks into underprice and overprice for all NSE 100 stocks with the help &beta; = Cov(r, r<sub>m</sub>)/Var(r<sub>m</sub>) and &alpha; = 0.05 (i.e., with risk free rate of 5%) to calculate the returns of stocks and then compare with actual stock returns.
- Markowitz portfolios were built by taking top 15 companies with high &beta; values, and performed 7000 simulations to achieve a parabolic effiecient frontier.
- Final portfolio was selected with the maximum Sharpe Ratio using **Capital Market Line (CML)** and invested in virtual stock trading platform [Money Bhai](https://moneybhai.moneycontrol.com/)

## Result:

-  With the final selected portfolio, a profit of x % was achieved over a period of y months.
