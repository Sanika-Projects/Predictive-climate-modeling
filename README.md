### Problem Statement
To develop solutions that can predict the occurrence of heat waves and the Air Quality Index (AQI) for Tier-2 cities of Telangana. The goal is to come up with innovative and effective ways to mitigate the impact of heat waves and poor air quality on the health and well-being of the residents in these cities. The solutions should be based on data-driven models and take into account various factors such as temperature, humidity, wind speed, and pollution levels.


### Demo




### solution
 - > In the project, data for Telangana's Tier 2 cities is fetched and stored in a CSV file. Using this data, data analysis and preprocessing is conducted in order to gain insightful information.

- > Using MAPE to assess the model's correctness, obtained a score that was reasonably low, indicating that the AQI prediction was accurate 

- >  Using maximum temperature data, forecasted heat waves. Overall, the approach offers a trustworthy way to anticipate AQI and heat waves in Telangana's Tier 2 cities.

- > The solution also involves retraining our model every seven days to improve the accuracy of our predictions. To achieve this, collected current data to update the historical data used to train the model. By doing so, the model can make more accurate predictions based on the most recent data available.




### Model

- >  The project involves the use of ***SARIMAX model***, a powerful time series forecasting model that can take into account both the time component and exogenous variables such as weather data. SARIMAX model allowed to accurately predict the AQI and identify periods of heat waves using historical data and current weather data obtained from APIs.
- > Evaluated the model's accuracy using Mean Absolute Percentage Error (MAPE). Our project also involved predicting heat waves using the temperature data obtained from Open Weather API.
- > Model Accuracy for :
- > Model Workflow 

<img width="773" alt="Screenshot 2023-03-04 at 9 35 23 PM" src="https://user-images.githubusercontent.com/96522398/222916487-ec0343a8-b1f4-4ee6-89fc-099cb7d716d3.png">


### Project Features

- Real-time AQI and Pollutants such as PM2.5, PM10, SO2, NO2 

- Real-time Weather with Temperature, Humidity and Wind Speed

- AQI and weather models are retrained every seven days, ensuring that the predictions remain accurate and relevant

- The project also includes an interactive graph that displays the Predicted AQI data and weather Data for the selected city
