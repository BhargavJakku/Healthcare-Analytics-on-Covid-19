# Healthcare-Analytics-on-Covid-19

**Project Goal:**

Analyze and forecast new COVID-19 cases in various countries using time series data and machine learning techniques.

**Data:**

Collected data from the "owid_f1.csv"  containing daily COVID-19 cases, deaths, and vaccination rates for various locations.

**Methodology:**

**Data Exploration and Cleaning:**

1. Loaded the dataset and explored its contents.
2. Handled missing values using forward filling.
3. Analyzed data distribution and identified null values.
4. Created custom functions for country-specific data exploration.

**Visualization and Comparison:**

1. Visualized new cases and deaths over time for the world and specific countries using line plots.
2. Analyzed vaccination rates and their correlations with case trends.
3. Developed a custom function "covid" to easily visualize data for individual countries.
   
**Time Series Forecasting:**

1. Defined a function "covidmodel" to build and train an RNN model for forecasting new cases based on moving averages.
2. Trained the model on historical data and validated its performance using RMSLE metrics.
3. Plotted actual vs. predicted cases for the validation set to visualize model accuracy.
   
**Prediction and Visualization:**

1. Created a function "covidpredit" to use the trained model and forecast new cases for a specified future period.
2. Appended predicted values to the original data and visualized both historical and forecasted trends.
   
**Country-Specific Analysis:**

1. Applied the entire analysis pipeline to individual countries like the UK, India, and Russia.
2. Generated separate models and forecasts for each country, offering localized insights.
   
**Results:**

This project demonstrates a comprehensive approach to COVID-19 data analysis and forecasting using time series modeling. It offers valuable insights and predictions for individual countries, highlighting the potential of data-driven approaches for public health preparedness and decision-making.
