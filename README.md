# Household-Energy-usage-Forecast


Energy is used everywhere and it is better to know how much energy is being used by each residential household. This information will provide energy companies with the knowledge necessary to adequately provide sufficient energy for their consumers at given times. The project will forecast the energy usage by each household for the coming n days. 
                      
Energy providers need to establish what the energy supply and demand will be in order to achieve customer satisfaction. Being able to predict how much consumers will need in the future can help companies make plans to avoid a shortage. This provides an overview of energy usage. 

 How to accurately forecast the energy use in a residential household with 15 minute and/or 1-hour smart meter * intervals for the next n days based on historical weather day and advanced metering infrastructure data is the high-level research question.  There are other notable questions. Is there seasonality affecting the use of energy? Does the time of day or day of week affect the amount of energy consumed? What are the location, demographics and other household features that correlate strongly with the amount of energy used?

There are two main data sources. The main data source is the Data port’s pecan street. This data provides energy use and demographic household information. This includes data at both 15-minute intervals and hourly intervals for electricity gauge readings. The second is the National Oceanic and Atmospheric Administration.  This data is provided by the airports nationwide and provides weather data at a level as granular as hourly. 

This plan has multiple steps, first being data cleaning and preprocessing includes checking correlations, null values, data distributions, and identifying patterns and trends (ie. seasonality and stationarity).  Since the data is time-related, the analysis will involve fitting time series models such as Exponential Smoothing and ARIMA. If the data is complex,  deep learning models such as Long Short Term Memory(LSTM) may provide better results using frameworks such as Tensorflow, Keras, Pytorch. The final step will be to compare the accuracy of the selected models to identify the best. 
