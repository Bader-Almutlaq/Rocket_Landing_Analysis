# SpaceX Falcon 9 First Stage Landing Analysis

This repository contains the Jupyter Notebooks and associated files for the IBM Data Science Capstone project on Coursera. The project focuses on analyzing the landing outcomes of the SpaceX Falcon 9 first stage and includes data collection, data wrangling, exploratory data analysis (EDA), predictive modeling, and visualization.

## Table of Contents

- [Project Structure](#project-structure)
- [Data Collection and Data Wrangling](#data-collection-and-data-wrangling)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Predictive Analysis](#predictive-analysis)
- [Results](#results)
  - [EDA with Visualization](#eda-with-visualization)
  - [EDA with SQL](#eda-with-sql)
  - [Interactive Map with Folium](#interactive-map-with-folium)
  - [Plotly Dash Dashboard](#plotly-dash-dashboard)
  - [Predictive Analysis Results](#predictive-analysis-results)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [License](#license)

## Project Structure

The repository is organized into the following Jupyter Notebooks, each corresponding to a specific task in the project:

1. `1_Data_Collection.ipynb` - Data collection
2. `2_Webscraping.ipynb` - Web scraping
3. `3_Data_Wrangling.ipynb` - Data wrangling methodology
4. `4_EDA_SQL.ipynb` - EDA with SQL
5. `5_Data_Visualization.ipynb` - Data visualization
6. `6_Interactive_Map_Folium.ipynb` - Interactive map with Folium
7. `7_Plotly_Dash_Dashboard.ipynb` - Plotly Dash dashboard
8. `8_Spacex_ML_Predictions.ipynb` - Predictive analysis (classification) results

## Data Collection and Data Wrangling

The data was collected from various sources, including the SpaceX API, and then wrangled to clean and preprocess it for analysis. Detailed methodology and steps are documented in `1_Data_Collection.ipynb` and `3_Data_Wrangling.ipynb`.

## Exploratory Data Analysis (EDA)

EDA was performed to uncover insights and patterns in the data. Interactive visual analytics techniques were used to make the exploration more insightful. Details can be found in `4_EDA_SQL.ipynb` and `5_Data_Visualization.ipynb`.

## Predictive Analysis

A predictive model was developed to classify the success of future SpaceX Falcon 9 first stage landings. The methodology and results are documented in `8_Spacex_ML_Predictions.ipynb`.

## Results

### EDA with Visualization

The results of the EDA using visualization techniques are documented in `5_Data_Visualization.ipynb`.

### EDA with SQL

SQL was used for data exploration and analysis. The results of these analyses are in `4_EDA_SQL.ipynb`.

### Interactive Map with Folium

An interactive map was created using Folium to visualize the landing sites. The results are documented in `6_Interactive_Map_Folium.ipynb`.

### Plotly Dash Dashboard

A Plotly Dash dashboard was developed to provide interactive visualizations of the analysis. The details can be found in `7_Plotly_Dash_Dashboard.ipynb`.

### Predictive Analysis Results

The results of the predictive analysis are documented in `8_Spacex_ML_Predictions.ipynb`.

## Conclusion

This project demonstrates the application of data science techniques to analyze and predict the outcomes of SpaceX Falcon 9 first stage landings. The methodologies and results provide valuable insights into the factors influencing landing success.

## Usage

To run the notebooks, clone this repository and open the notebooks in Jupyter Notebook or JupyterLab. Ensure you have the necessary dependencies installed, which can be found in the `requirements.txt` file.

```bash
git clone https://github.com/yourusername/spacex-landing-analysis.git
cd spacex-landing-analysis
pip install -r requirements.txt
jupyter notebook
