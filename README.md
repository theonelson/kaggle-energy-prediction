# kaggle-energy-prediction

date : 12/2022
Kaggle competition : prediction of the energy prices 

## Description of the subject 

In this dataset you have informations like weather from a nearby station, air temperature and wind speed, and data multiple captors in low-energy houses. Your target variable is Appliances. You must construct models in order to predict it.

The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru), and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non predictive attributes (parameters).

The dataset you have contains 29 columns. The column Appliances is the target variable that describes energy use in Wh . You must construct models in order to predict it using the other columns.

Here the other 28 columns you will find in the dataset:

- lights : energy use of light fixtures in the house in Wh
- T1 : Temperature in kitchen area, in Celsius
- RH_1 : Humidity in kitchen area, in %
- T2 : Temperature in living room area, in Celsius
- RH_2 : Humidity in living room area, in %
- T3 : Temperature in laundry room area
- RH_3 : Humidity in laundry room area, in %
- T4 : Temperature in office room, in Celsius
- RH_4 : Humidity in office room, in %
- T5 : Temperature in bathroom, in Celsius
- RH_5 : Humidity in bathroom, in %
- T6 : Temperature outside the building (north side), in Celsius
- RH_6 : Humidity outside the building (north side), in %
- T7 : Temperature in ironing room , in Celsius
- RH_7 : Humidity in ironing room, in %
- T8 : Temperature in teenager room 2, in Celsius
- RH_8 : Humidity in teenager room 2, in %
- T9 : Temperature in parents room, in Celsius
- RH_9 : Humidity in parents room, in %
- T_out : Temperature outside (from Chièvres weather station), in Celsius
- Press_mm_hg : Pressure (from Chièvres weather station), in mm Hg
- RH_out : Humidity outside (from Chièvres weather station), in %
- Windspeed : Wind speed(from Chièvres weather station), in m/s
- Visibility : Visibility (from Chièvres weather station), in km
- Tdewpoint : Tdewpoint (from Chièvres weather station), °C
- rv1 : Random variable 1, nondimensional
- rv2 : Rnadom variable 2, nondimensiona
- Day_of_week : Day of week
