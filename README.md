# Weather prediction system
 Weather forecasting is crucial for various sectors like agriculture, transportation, and emergency preparedness. Traditional methods use meteorological data, but AI/ML techniques offer enhanced accuracy by analysing vast datasets and patterns. This project aims to leverage AI/ML algorithms in Python to forecast weather accurately by processing historical weather data. The use of Python and various ML algorithms facilitates better forecasting, aiding decision-making in multiple sectors reliant on weather predictions. By analysing historical weather data, including temperature, humidity, wind speed, and other relevant factors, various machine learning models such as regression, neural networks, or decision trees are trained to predict future weather patterns. Through the implementation of these algorithms in Python, the project seeks to develop a robust system capable of providing more precise short-term and long-term weather predictions, aiding in proactive decision- making and risk management across various sectors reliant on weather information.  Objective: Weather prediction using machine learning involves several objectives aimed at improving forecasting accuracy, efficiency, and the understanding of weather patterns. Here are some key objectives:  •	Improved Accuracy: Enhance the precision of weather forecasts by developing machine learning models that can better analyze and predict weather patterns based on historical data.  •	Extreme Weather Prediction: Focus on predicting extreme weather events like hurricanes, storms, heatwaves, or heavy rainfall to provide timely warnings and mitigate potential damages.  •	Localized Predictions: Improve the resolution and accuracy of forecasts for specific regions or localities by considering microclimates and other localized factors influencing weather.  •	Real-Time Updates: Develop systems capable of continuous learning and updating based on real-time data inputs, ensuring the model adapts to changing weather conditions swiftly.  •	Model Interpretability: Enhance the interpretability of machine learning models to better understand the reasoning behind specific weather predictions, aiding meteorologists in decision-making processes.  •	User-Friendly Interfaces: Develop user-friendly applications or interfaces to disseminate weather forecasts effectively, making them accessible and understandable to the general public and various industries.  By focusing on these objectives, weather prediction using machine learning aims to revolutionize forecast accuracy, timeliness, and accessibility, thereby enabling better preparedness and decision-making in various sectors affected by weather fluctuations. 

 There are two purposes of my project. One of the purposeis to forecast the status of weather in the August of specific year. I will demonstrate the result through using decision tree regression and show the output for the status of wet or heat. Another aim is to predict the temperature using different algorithms like linear regression, random forest regression and K-nearest neighbor regression. The output value should be numerical based on multiple extra factors like population density and air health quality.

 To forecast the status of weather in the August of next year
**ML Algorithm**: Decision Tree Regression
**Status**: wet and heat 
**Output Value**: Yes / No
To predict the temperature using Different Algorithms
**ML Algorithms**: Linear Regression,
	 	Random Forest Regression, K-Nearest Neighbor


**Algorithm - Decision Tree:**  builds regression or classification models in the form of a tree structure
**Algorithm - Linear Regression:** performs the task to predict a dependent variable value (y) based on a given independent variable (x)
**Algorithm - Random Forest Regression:** performing both regression and classification tasks using multiple decision trees and a statistical technique called bagging
**Algorithm - K-Nearest Neighbor Regression**

**Data Source:** Hong Kong Observatory, aqhi.gov.hk
**Dynamic Data:** August of 1999 - 2019
**Static Data:** June of 2014 - 2019

**

## Data Description:

**
**mean_temp:** mean air temperature
**max_temp:** mean daily maximum air temperature
**min_temp:** mean daily minimum air temperature
**meanhum:** mean relative humidity
**meandew:** mean dew point temperature
**pressure:** mean daily air pressure
**heat:** true when mean air temperature is over or equal to 30
**wet:** true when mean relative humidity is over or equal to 80
**Mean_cloud:** mean cloud
**population:** population density
**Sunshine_hour:** mean number of hour of sunshine
**Wind_direction:** mean wind direction
**Wind_speed:** mean wind speed
**Air_health_quality:** mean daily air health quality

**

## System Requirement:

**
Python 3.6
BeautifulSoup
Pandas
Numpy
Matplotlib
Seaborn
Openpyxl
Sklearn
wxPython

**
