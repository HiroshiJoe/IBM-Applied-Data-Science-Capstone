# SpaceX Falcon 9 Launch Analysis - IBM Applied Data Science Capstone

This repository contains the code and resources for the IBM Applied Data Science Capstone project, focusing on analyzing SpaceX Falcon 9 launch data.

## Project Overview

This project analyzes the data from SpaceX launches to determine the success rates of Falcon 9's first-stage landings and to explore the factors that impact these outcomes. The analysis includes data collection, data wrangling, exploratory data analysis (EDA), geospatial analysis, and machine learning to predict landing success.

## Files and Notebooks

- **Data Collection Api.ipynb**  
  - Collects launch data from the SpaceX API, processes it into a DataFrame, and prepares it for further analysis.
  
- **Data Collection Webscraping.ipynb**  
  - Scrapes additional Falcon 9 and Falcon Heavy launch data from Wikipedia using BeautifulSoup, converting the results into a DataFrame.
  
- **Data Wrangling.ipynb**  
  - Performs preliminary data wrangling, including cleaning, transforming, and merging data from multiple sources to prepare it for analysis.
  
- **EDA.ipynb**  
  - Conducts Exploratory Data Analysis (EDA) to discover patterns and correlations in the data, providing insights into the factors affecting the success of Falcon 9 landings.
  
- **EDA SQL.ipynb**  
  - Implements SQL queries on the dataset to answer specific questions about launch outcomes using an IBM DB2 cloud instance.
  
- **Folium.ipynb**  
  - Uses Folium to create an interactive map, analyzing the geospatial data of launch sites and their proximity to various features like railways, highways, and coastlines.
  
- **Machine Learning.ipynb**  
  - Builds and evaluates several classification models (Logistic Regression, SVM, Decision Tree, KNN) to predict the success of Falcon 9 landings.
  
- **Plotly Dashboard.py**  
  - Develops an interactive dashboard using Plotly Dash to visualize the results of the analysis and provide an intuitive interface for exploring the data.

## How to Run

1. Clone the repository to your local machine.
2. Ensure you have the necessary Python libraries installed (e.g., pandas, numpy, seaborn, matplotlib, folium, plotly, scikit-learn, etc.).
3. Open each Jupyter notebook (.ipynb) and run the cells to reproduce the analysis.
4. Use `Plotly Dashboard.py` to launch the interactive dashboard.

## Project Summary

The analysis in this project helps determine which factors are most influential in the success of Falcon 9 landings. The use of geospatial analysis, machine learning, and interactive visualization provides a comprehensive understanding of the data and valuable insights for SpaceX's future launches.

## Acknowledgments

This project is part of the IBM Applied Data Science Capstone on Coursera. The data was collected from SpaceX API and Wikipedia.
