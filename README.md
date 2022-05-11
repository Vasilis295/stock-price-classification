# stock-price-classification


In this mini project we contacted regression and classification based on nasdaq stock prices, GDP for USA, Fed balance sheet expansion, share buy backs index and corporate profits.
In the first file we explore gdp and corporate profits as independend variables vs nasdaq as the target. After all needed data cleaning and transformation, we did a regression which gave us a score of 0.73. 
However, with polynomial regression the score rose to 0.92, indicating probably a non-linear relationship.
In the second file we added the Fed liquidity(balance sheet) and this rose linear regression score to 0.98 and polynomial to 0.99 which is near perfect expanatory power. 
In the classification however, there was a difficulty in predicting a fall in prices, as quarterly falls in the period examined were very few.
In the third we had buybacks, Fed balance sheet and Nasdaq. Regression score was 0.83 and not higher with polynomial. Then we explored many different techniques in classification for imbalanced datasets, which helped us a bit in raising classification score to 0.6 but also uncovering these interesting techniques/
Data from FRED.
