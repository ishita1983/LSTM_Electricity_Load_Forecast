## WIDS Texas Datathon 2021: Prediction of Electricity Load 

By [Ishita Chakraborty](https://www.linkedin.com/in/ishitachakrabortyphd/)


This notebook explores the prediction of electrical load for 7 days into the future using historical data of Texas and predicted weather for the 7 days. A multi-layer LSTM model is trained for forecasting hourly electricity usage.

This work is submitted as an entry to the WiDS Texas Datathon 2021. The input data to the model is stored in a git repo and updated every day. In the current state of the notebook, the forecasting is for June 13 to June 20,2021.


### Explore data
Explore the available data with plots and charts.

The map below shows the different weather zones in Texas. We will use this to track the cities related to the weather zones and pull out the zonal weather history and weather prediction.

![Weather Zone Maps](https://raw.githubusercontent.com/ishita1983/LSTM_Electricity_Load_Forecast/main/ercotWeatherZoneMap.png)
