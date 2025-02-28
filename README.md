# Indian Cities Air Quality Analysis

## Overview
This project analyzes air quality data from various Indian cities using Python. The analysis includes data preprocessing, visualization, and insights derived from air pollution metrics such as PM2.5, PM10, NO2, SO2, CO, and other pollutants.

## Dataset
The dataset contains air quality measurements collected from multiple cities in India. It includes:
- **City Name**
- **Date and Time**
- **Air Pollutant Levels** (PM2.5, PM10, NO2, SO2, CO, O3, etc.)
- **Meteorological Data** (if available)

## Features
- **Data Cleaning & Preprocessing**: Handling missing values, standardizing formats, and filtering invalid entries.
- **Exploratory Data Analysis (EDA)**: Statistical summaries and visualizations of air pollutant distributions across cities.
- **Time Series Analysis**: Trends and seasonal variations in air pollution levels.
- **Geospatial Analysis**: Mapping air quality index (AQI) across different locations.
- **Prediction Models**: Implementing machine learning models for forecasting air quality trends.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Harg2411/Indian-Cities-Air-Quality-Analysis.git
   cd indian-cities-air-quality
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Open `indian-cities-air-quality-analysis.ipynb` in Jupyter Notebook and execute the cells.

## Dependencies
The project requires the following Python libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Folium (for geospatial analysis)

Install dependencies using:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn folium
```

## Usage
1. Load the dataset into the notebook.
2. Preprocess and clean the data.
3. Perform exploratory data analysis to understand air pollution trends.
4. Use machine learning models to predict future air quality trends.
5. Visualize geospatial air quality data on an interactive map.

## Results
- Insights into air pollution trends across major Indian cities.
- Identification of seasonal variations and sources of pollution.
- Predictive models for forecasting air quality trends.
