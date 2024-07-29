# Weather_Prediction

This project aims to enhance weather prediction using machine learning techniques. Here I use a dataset of weather conditions in Seattle and employ a Random Forest classifier to predict the weather based on precipitation, temperature, and wind data.

## Dataset

The dataset used in this project is `seattle-weather.csv`, which contains daily weather data for Seattle from 2012 to 2015. The columns in the dataset are:
- `date`: The date of the observation.
- `precipitation`: The amount of precipitation in mm.
- `temp_max`: The maximum temperature of the day in degrees Celsius.
- `temp_min`: The minimum temperature of the day in degrees Celsius.
- `wind`: The average wind speed in m/s.
- `weather`: The weather condition (drizzle, rain, sun, snow, fog).

## Installation

To run this project, you need to have Python installed along with several libraries. You can install the required libraries using the following command:

```bash
pip install pandas matplotlib numpy seaborn scikit-learn
