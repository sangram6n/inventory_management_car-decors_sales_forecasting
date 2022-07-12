# Inventory Management Car decors Sales Forecasting
	1)this is my data science project repository
	2)here we are predicting the sales unit for car decors items for next 12 months
	3) performed EDA data visualisation
	4) There are 22 features for each field we have devloped model and made the model pickle file
	5) then we deployed the model through streamlit framework
	
# Tools used
	1) Numpy
	2) Pandas
	3) Statsmodel
	4) Fbprophet
	5) Autotime series
	6) Mysql
	7) Mysql conector API
	8) Altair
	9) Matplotlib
	10) Streamlit
	
	
# Model Building 
	1)in model building i have used sarima ,holt winters,auto time series 
	2) but most prominent and accurate results are found in case of sarima and holt winter
	3) due to lower amount of data the LSTM model could not perform better
	4) we also tested auto time series and facebook profet for model building

# Evaluation Metrices
	1) MAPE(mean abosolute percentage error) --> We go  for the best model selection on the basis of MAPE in Most of the cases
	2) AIC (Akaike Information Criterion)
	3) RMSE (Root Mean Square Error)
# Model Deployment
	1)here i have choosed streamlit frame work for model deployment
	2)for data visualisation purpose we have used Altair library of python
