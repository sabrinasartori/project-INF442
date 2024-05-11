# My Project INF 442-1 Readme

## Predicting Household Power Consumption using Meteorological Data

### About the Project
This project, assigned under INF 442-1, involved conducting a feasibility study to predict household power consumption patterns based on meteorological data.

### Overview
The project was inspired by previous research, although we utilized a distinct dataset for our analysis. Unlike our exercise sessions, we had the liberty to choose any programming language or tool that suited our needs and comfort level. This flexibility enabled us to streamline tasks like data cleaning and visualization, facilitating a more comprehensive analysis.

### Data
Our analysis relied on two main datasets:

1. **Household Power Consumption:** Spanning nearly four years, this dataset featured minute-level measurements of electric power consumption from a household in Sceaux, France. Attributes included global active and reactive power, voltage, current intensity, and sub-metering readings.

2. **Meteorological Data:** Sourced from Météo France public database, this dataset provided meteorological measurements at a three-hour sampling rate. Parameters such as pressure, wind speed, temperature, and humidity were included.

### Tasks Completed
1. **Data Pre-processing:** Cleaning and outlier detection were pivotal to ensure data accuracy. We employed the Z-score method for outlier detection and integrated cleaned data from both datasets by matching timestamps and location. Missing data was filled using interpolation techniques.

2. **Seasonality Detection:** Leveraging clustering techniques, we identified distinct periods of the year with similar power consumption patterns. Implementing the K-means algorithm on daily data vectors facilitated comparison and insight generation.

3. **Distribution of Hourly Consumption:** Analyzing the shape of hourly power consumption distributions revealed interesting patterns. We conducted normality tests and compared distributions across different seasons to understand variations in consumption behavior.

4. **Weather Influence:** Exploring correlations between weather conditions and power consumption shed light on the impact of temperature variations. Using data from previous years, we estimated power consumption for the subsequent year and compared it with actual data to validate our predictions.

### Conclusion
This project offered valuable insights into household power consumption dynamics and its correlation with meteorological factors. By leveraging advanced analytical techniques and tools, we were able to uncover meaningful patterns and trends, contributing to the broader understanding of energy consumption behavior.
