# Seoul_Bike_Sharing_Prediction!

**Problem Statement:**
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
![bbk](https://user-images.githubusercontent.com/113902042/211993290-73f15f51-6b83-4822-89f9-220704079ecf.jpg)

#**Data Description:**
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

#**Attribute Information:**

• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

#**Data Pipeline:**

● **Exploratory Data Analysis (EDA):** In this part we have done some EDA on the features to see the trend.

● **Data Processing:** In this part we went through each attributes and encoded the categorical features.

● **Model Creation:** Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

#**Observations:**

● **Observation 1:** In the Model Evaluation Matrices table, Linear Regression, Polynomial Linear regression is done.

● **Observation 2:** Random forest has performed better than Decision Trees in terms of adjusted r2.

● **Observation 3:** We are getting the best results from XGB model. So it is advisable to deploy XGBoost Gridsearch CV model.

#**Conclusions:**

● We started with loading the data, then we did Exploratory Data Analysis (EDA), null values treatment, feature selection, encoding of categorical columns, and then model building. In all of these models, our accuracy ranges from 56% to 91%, which can be said to be good for such a large dataset. This performance could be due to various reasons like the proper pattern of data, large data, or because of the relevant features.

● After performing variable importance analysis to find the most significant variables for all the models developed with the given data sets. We are getting the best results from XG Boost model.
