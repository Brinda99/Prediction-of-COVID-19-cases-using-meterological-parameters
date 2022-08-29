# Prediction-of-COVID-19-cases-using-meterological-parameters
The need for accurate and advanced prediction of Covid19 cases is increasing by day. The coronavirus pandemic has been declared a health emergency of international concern by the World Health Organization for 2020. India has recorded a record high of more than 40,000 new case on April 30, 2021. Current study talks about possible relationship of Covid19 transmission with meteorological parameters namely humidity, temperature, rain, speed, and pressure. The weather data been collected from NASA archives. The daily number of confirmed Covid cases, deaths and recovered were extracted from a public website (https://data.covid19india.org/). Aggregated daily data was combined for a specific state for approximately nine months from 01-01-2021 and converted into a multivariable time series data frame. We then tried to build a Bi-LSTM architecture that gives the highest accuracy in predicting the number of confirmed Covid cases for n days based on given data.

## Methodology

The climate data containing daily aggregate for temperature, precipitation, pressure, windspeed and humidity for all the districts of Kerala was collected from a NASA repository. (https://power.larc.nasa.gov/data-accessviewer/).Large volumes of data are required for model construction in neural network applications. In this research,
the data used for model development included the number of confirmed Covid19 positive cases and weather parameter measurements such as temperature, humidity, wind speed, pressure, rain etc. The Covid19 data collected includes the number of confirmed cases, deaths and recovered for a day.(https://data.covid19india.org/). The
lockdown effect on different states of India is different. Hence in a bid to reduce the bias in our data and to build an accurate model, we decided to focus only on the state of Kerala, which had the highest number active covid19 cases in India when this paper was being written. We considered different districts of Kerala and for each district, we
collected the weather data from a website of NASA. Then we tried to predict the daily Covid19 positive cases in each of the district based on the past confirmed covid cases of the district along with its weather data.

![image](https://user-images.githubusercontent.com/59830753/187105389-3948b6f3-54d7-4083-9ea7-aa88387cfd82.png)


