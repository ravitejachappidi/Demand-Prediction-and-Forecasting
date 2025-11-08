# Demand-Prediction-and-Forecasting
This Project is about the prediction and forecast of sales.

The dataset is straightforward with columns as follows:

record_ID ||	week ||	store_id ||	sku_id ||	total_price ||	base_price ||	is_featured_sku ||	is_display_sku ||	units_sold

The target variable being:  units_sold 
The rest of the columns are input variable.

The prediction is basically a regression problem. The Code attempts different regression algorithms to train and test the data and get the best algorithm.

As for forecasting, This project uses facebook's - Prophet and other statistical algorithms within python for forecasting.
It mainly uses just the date and store_id for grouping the data, and uses the algorithms for prediction.
Here the testing data is same as training dataset with last 10% of the non trained data, for comparision of sales with forecasted model.
 
