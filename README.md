<b>Title</b>: "Gold Price Prediction Using Data Analysis & Machine Learning"

<b>Description</b>: Gold, a valuable commodity, often experiences price fluctuations due to various economic factors, including inflation, currency value, and geopolitical events. This project explores the relationships between these factors and historical gold prices, and uses machine learning to predict future price trends.
The goal is to develop a predictive model that can accurately forecast gold prices over short-term periods, providing a tool for financial planning and risk management.
This project aims to predict future trends in gold prices by analyzing historical data and leveraging machine learning algorithms. Through this predictive model, we aim to assist investors and analysts in understanding potential fluctuations in the gold market.

<b>Dataset</b> :The dataset for this project contains historical gold prices and related financial indicators, sourced from [dataset source - Kaggle]. Key attributes in the dataset include:

Date: The date of the recorded price.

Gold Price: Daily closing price of gold.

Economic Indicators: 
SPX(S&P 500Index)used in predicting asset prices(stocks,commodities,etc.), 
USD (U.S. Dollar Index or Exchange Rates) ,
USO (United States Oil Fund), 
iShares Silver Trust ETF (SLV), which is an exchange-traded fund that aims to track the price of silver.

Dataset Summary:

Data Source: [https://www.kaggle.com/altruistdelhit...]

Time Period: [2016-present]

We experimented with multiple models to find the best-performing approach for our gold price predictions:

<b>Modeling Approach</b>:

<b>ARIMA</b> (AutoRegressive Integrated Moving Average): A statistical time-series model.

<b>LSTM</b> (Long Short-Term Memory): A deep learning model suited for sequential data.

<b>Random Forest Regression</b>: A machine learning model for capturing non-linear relationships.


<b>Evaluation Metrics</b>

To evaluate the model’s performance, we used R-squared (R²) and correlation metrics:

<b>R-squared (R²):</b>
 R-squared, or the coefficient of determination, measures the proportion of variance in the actual gold prices explained by the model's predictions. An R² value closer to 1 indicates that the model accounts for most of the variability in the data, showing high predictive power.

<b>Correlation</b>:
Correlation measures the linear relationship between the predicted and actual gold prices. A positive correlation close to +1 suggests a strong agreement between predicted and actual values, while a lower correlation implies a weaker relationship.


<b>RESULTS</b>:

The best-performing model, the Random Forest Regressor, achieved the following results:

Metric	Value

![image](https://github.com/user-attachments/assets/0a6a46bd-c095-4a51-98ac-28718c0ce3b1)





These results show that the model can capture gold price trends effectively, though there is still room for improvement, especially in periods of high volatility.



![image](https://github.com/user-attachments/assets/97fd3ec4-c35d-42d6-874e-37d6c7810e99)



<b>Future Work</b>

To enhance the model's predictive power, future steps could include:

<b>Incorporating Additional Features</b>: Such as interest rates, crude oil prices, and other commodities.


<b>Real-Time Predictions</b>: Setting up an API to generate real-time forecasts for gold prices







<b>Conclusion</b>

This gold price prediction model provides a useful tool for analyzing and forecasting market trends. While reasonably accurate, improvements can be made by refining the model or expanding the dataset. Predictive models like this can offer valuable insights, assisting investors and economists in making informed decisions.






