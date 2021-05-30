# MLinStockMarket
Source code of my theisis(written in Turkish): “Makine Öğrenmesi Algoritmaları ile Hisse Senedi Hareket Yönü Tahmini” [Predicting the Direction of Stock Market Prizes with Machine Learning Algorithms], 3. Ulusal Başkent Disiplinler Arası Bilimsel Çalışma Kongresi, 2021

You can find full text here : https://www.izdas.org/books

Contact me at: umutcanakdag@hotmail.com

SUMMARY 

General state of the economy, political events and the investor's expectation from the investment cause fluctuations in stock prices. This complex nature of stock prices makes the prediction of stock movement direction very difficult. In this study, various machine learning methods are used to overcome this difficulty and to make various comparisons on the results. In addition to the daily High, Low, Close, Open, Volume values, 11 different technical indicators are calculated and used as inputs to the models. Logistic Regression, Support Vector Machines, K-Nearest Neighbors, Decision Trees, Random Forest, Gradient Boosting methods are tested and results are compared. 
Besides comparing machine learning models, in addition to the data at t_0, those at t_(-1), t_(-2), t_(-3) and t_(-4)  are also tried as input, and it is tested whether the use of the previous days in the independent variable improves the performance or not. For a better comparison with previous studies, time series of Apple stock price is used in this experiment. Target variable is reconfigured for the movement of the stock price after 1, 7, 14 and 21 days, so it is tested whether the short-term forecast or the long-term forecast gives more efficient results. As a result, it has been observed that the best estimator is the Random Forest classifier. The maximum accuracy that can be reached is found to be 86%. Besides, it has been found out that using the data of previous days as input has no effect on prediction. In addition, it has been concluded that long-term forecasts are much more successful than short-term forecasts.
