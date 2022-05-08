# Electricity-Price-Prediction-using-Random-Forest-Regressor

The price of electricity depends on many factors. Predicting the price of electricity helps many businesses understand how much electricity they have to pay each year. The Electricity Price Prediction task is based on a case study where you need to predict the daily price of electricity based on the daily consumption of heavy machinery used by businesses. So if you want to learn how to predict the price of electricity, then this repository is for you.

Suppose that your business relies on computing services where the power consumed by your machines varies throughout the day. You do not know the actual cost of the electricity consumed by the machines throughout the day, but the organization has provided you with historical data of the price of the electricity consumed by the machines. Below is the information of the data we have for the task of forecasting electricity prices:

DateTime: Date and time of the record
Holiday: contains the name of the holiday if the day is a national holiday
HolidayFlag: contains 1 if it’s a bank holiday otherwise 0
DayOfWeek: contains values between 0-6 where 0 is Monday
WeekOfYear: week of the year
Day: Day of the date
Month: Month of the date
Year: Year of the date
PeriodOfDay: half-hour period of the day
ForcastWindProduction: forecasted wind production
SystemLoadEA forecasted national load
SMPEA: forecasted price
ORKTemperature: actual temperature measured
ORKWindspeed: actual windspeed measured
CO2Intensity: actual C02 intensity for the electricity produced
ActualWindProduction: actual wind energy production
SystemLoadEP2: actual national system load
SMPEP2: the actual price of the electricity consumed (labels or values to be predicted)

So our task here is to use this data to train a machine learning model to predict the price of electricity consumed by the machines.
