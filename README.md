# Weather Analysis Project

![images](https://github.com/user-attachments/assets/09d25d62-4950-40c8-bb82-cedb44cd5965)


This project analyzes a dataset of weather observations recorded hourly over a year. The data includes various attributes such as temperature, dew point, relative humidity, wind speed, visibility, pressure, and weather conditions. Visualizations and statistical summaries are used to understand patterns and trends.

## Dataset Description

The dataset contains **8,784 entries** with the following columns:
- `Date/Time`: Timestamp of the observation.
- `Temp_C`: Temperature in Celsius.
- `Dew Point Temp_C`: Dew point temperature in Celsius.
- `Rel Hum_%`: Relative humidity as a percentage.
- `Wind Speed_km/h`: Wind speed in kilometers per hour.
- `Visibility_km`: Visibility in kilometers.
- `Press_kPa`: Atmospheric pressure in kilopascals.
- `Weather`: Weather conditions as a categorical variable.

## Key Features

1. **Data Preprocessing**:
   - Conversion of the `Date/Time` column to a datetime object for time-based analysis.
   - Basic statistical summaries using `.info()` and `.describe()` provide insights into the dataset, including count, mean, standard deviation, and ranges of numeric attributes.

2. **Exploratory Data Analysis (EDA)**:
   - **Time Series Analysis**:
     - Temperature trends over the year show seasonal variations, with peaks in summer and troughs in winter.
     - Relative humidity trends highlight periods of higher or lower moisture levels.
     - Wind speed and atmospheric pressure trends provide insights into dynamic weather conditions.
     - Visibility trends reveal periods of reduced visibility due to weather phenomena like fog or precipitation.
   - **Distribution Analysis**:
     - Histograms with density curves visualize the distribution of temperature, dew point, humidity, wind speed, pressure, and visibility.
     - Skewness and common ranges of values for each attribute are explored.
   - **Correlation Analysis**:
     - A heatmap is generated to visualize the correlation between numeric variables, identifying strong and weak relationships among them.

3. **Visualizations**:
   - Line plots and histograms for temporal and distribution analysis.
   - Correlation heatmap for identifying relationships between numeric variables.
   - All visualizations are created using **Seaborn** and **Matplotlib** libraries.

## Project Highlights

1. **Temperature Trends**:
   - Clear periodic patterns in temperature due to seasonal changes.
   - Visualized using a line plot with temperature on the y-axis and time on the x-axis.

2. **Dew Point Temperature Distribution**:
   - Histogram with a density curve reveals most dew point values between 0°C and 10°C.

3. **Relative Humidity Analysis**:
   - Humidity values are concentrated between 60% and 80%, as shown in the histogram.

4. **Wind Speed Trends**:
   - A skewed distribution shows most wind speeds are moderate, with occasional spikes.

5. **Pressure Analysis**:
   - Pressure values are mostly stable, following a near-normal distribution.

6. **Correlation Matrix**:
   - A heatmap identifies relationships between attributes such as temperature, humidity, and pressure.

## Requirements

To run the project, install the following Python libraries:
- `pandas`
- `seaborn`
- `matplotlib`

You can install the required libraries using:
```bash
pip install pandas seaborn matplotlib
