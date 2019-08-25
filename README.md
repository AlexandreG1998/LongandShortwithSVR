# Long and Short with SVR
This is a SVR used in a Long and Short trading strategy

## Objective:

Verify if it's possible to trade with a Long and Short portfolio powered by a Support Vector Regressor Model optimized with Monte Carlo Simulations

## Steps

1 - Download data from good sources like Quandl
2 - Prepare data with datetime adjust and Close's log values
3 - Write core functions to generate SVR by pairs and Monte Carlo Simulations
4 - Prepare all pairs
5 - Split dataset
6 - Granger Cointegration Test ( < 5%  ADF test to pass )
7 - Backtest and compare Buy and Hold vs Long and Short powered with SVR vs Long and Short powered with SVR and Monte Carlo filter

