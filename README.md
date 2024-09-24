This project was created with the purpose to forecast GDP of the Republic of Belarus and compare the forecast with the real numbers.
I used the real month GDP volume for the years 2017-2023 to train the model. 

Seasonal ARIMA model was chosen as I noticed seasonality in the data. The decline in GDP in February can be explained by calendar factor (February is the shortest month of a year). And the growth of GDP volume in autumn is explained by harvesting and growth in food production as agricultural sector brings a lot of input in GDP of Belarus.

RMSE of the forecast is rather low (0,351 compared to average GDP volume around 19 bn).
The model showed very good results in the first 3 periods:
month        forecasted GDP        real GDP
Jan'24          18,14                18,0
Feb'24          16,40                16,5
Mar'24          18,63                18,5
