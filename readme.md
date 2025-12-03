Daily Public Transport Passenger Journey 

1.Model used :Prophet(Time series model) 
Prophet is a decomposable forecasting model developed by Facebook (Meta) for handling time series data with:

1.Trend

2.Seasonality

3.Holidays/Events

4.Irregularities (outliers, missing values)

->Prophet works on the following additive model:

y(t)=g(t)+s(t)+h(t)+ϵt

Where:
g(t) → Trend function
s(t) → Seasonal components (daily, weekly, yearly, monthly if added)
h(t) → Holiday effects (optional)
ε(t) → Error term 


Prophet model is used:

1.Dataset contains data daily.

2.Dataset contains weekly patterns(weekday vs weekends)

3.Dataset contains yearly patterns(school seasons)

4.prophet can handle missing values,outliers


2.Prophet Parameters used:
1.Data preparation parameters-ds column data column,y column (target variable)
3.Seasonality Parameters-Weekly_Seasonality,yearly_seasonality


