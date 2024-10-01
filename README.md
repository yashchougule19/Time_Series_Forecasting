# Time_Series_Forecasting

For better understanding, I have kept two separate notebooks, 
one for RNN (RNN_Time_Series_Forecasting.ipynb) and 
the other for MLP (MLP_Time_Series_Forecasting.ipynb).

I have implemented the algorithm to do rolling forecast with MLP regressor however the results are not very impressive. The reason is some lacking steps in data wrangling.
For this, I combined the train and test set  beforehand in excel to create their lag features. 
The MLP regressor notebook is processed on this dataset.
