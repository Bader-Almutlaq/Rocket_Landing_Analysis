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

## Introduction

This project is part of the IBM Data Science Capstone course on Coursera. The aim is to analyze the outcomes of the SpaceX Falcon 9 first stage landings and predict the success of future landings. 

## Project Structure

The repository is organized into the following Jupyter Notebooks, each corresponding to a specific task in the project:


1. `2_Data_Collection_Wrangling.ipynb` - Data collection and data wrangling methodology
2. `3_EDA_Interactive_Visual_Analytics.ipynb` - EDA and interactive visual analytics methodology
3. `4_Predictive_Analysis_Methodology.ipynb` - Predictive analysis methodology
4. `5_EDA_Visualization_Results.ipynb` - EDA with visualization results
5. `6_EDA_SQL_Results.ipynb` - EDA with SQL results
6. `7_Interactive_Map_Folium_Results.ipynb` - Interactive map with Folium results
7. `8_Plotly_Dash_Dashboard_Results.ipynb` - Plotly Dash dashboard results
8. `9_Predictive_Analysis_Results.ipynb` - Predictive analysis (classification) results

## Data Collection and Data Wrangling

The data was collected from various sources, including the SpaceX API, and then wrangled to clean and preprocess it for analysis. Detailed methodology and steps are documented in `2_Data_Collection_Wrangling.ipynb`.

## Exploratory Data Analysis (EDA)

EDA was performed to uncover insights and patterns in the data. Interactive visual analytics techniques were used to make the exploration more insightful. Details can be found in `3_EDA_Interactive_Visual_Analytics.ipynb`.

## Predictive Analysis

A predictive model was developed to classify the success of future SpaceX Falcon 9 first stage landings. The methodology is documented in `4_Predictive_Analysis_Methodology.ipynb`, and the results are in `9_Predictive_Analysis_Results.ipynb`.

## Results

### EDA with Visualization

The results of the EDA using visualization techniques are documented in `5_EDA_Visualization_Results.ipynb`.

### EDA with SQL

SQL was used for data exploration and analysis. The results of these analyses are in `6_EDA_SQL_Results.ipynb`.

### Interactive Map with Folium

An interactive map was created using Folium to visualize the landing sites. The results are documented in `7_Interactive_Map_Folium_Results.ipynb`.

### Plotly Dash Dashboard

A Plotly Dash dashboard was developed to provide interactive visualizations of the analysis. The details can be found in `8_Plotly_Dash_Dashboard_Results.ipynb`.

### Predictive Analysis Results

The results of the predictive analysis are documented in `9_Predictive_Analysis_Results.ipynb`.

## Conclusion

This project demonstrates the application of data science techniques to analyze and predict the outcomes of SpaceX Falcon 9 first stage landings. The methodologies and results provide valuable insights into the factors influencing landing success.

## Usage

To run the notebooks, clone this repository and open the notebooks in Jupyter Notebook or JupyterLab. Ensure you have the necessary dependencies installed, which can be found in the `requirements.txt` file.

```bash
git clone https://github.com/yourusername/spacex-landing-analysis.git
cd spacex-landing-analysis
pip install -r requirements.txt
jupyter notebook
