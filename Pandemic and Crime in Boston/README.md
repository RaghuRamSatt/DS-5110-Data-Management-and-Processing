# Pandemic and Crime in Boston Analysis

This folder contains the analysis of crime rates in Boston during the COVID-19 pandemic.

## Detailed Documentation

For a comprehensive explanation of the analysis, methodology, and results, please refer to the [Pandemic Conditions and Their Influence on Crime Rates in Boston Neighborhoods.pdf](./Pandemic%20Conditions%20and%20Their%20Influence%20on%20Crime%20Rates%20in%20Boston%20Neighborhoods.pdf) file in this folder.

## Files

- `Pandemic Conditions and Their Influence on Crime Rates in Boston Neighborhoods.ipynb`: Jupyter notebook containing the main analysis
- `Pandemic Conditions and Their Influence on Crime Rates in Boston Neighborhoods.pdf`: Detailed report of the analysis
- `requirements.txt`: List of Python packages required to run the notebook
- `data/`: Folder containing the datasets used in the analysis (not included in the repository)

## Setup

1. Ensure you have Python 3.7+ installed
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Analysis

Open the Jupyter notebook and run the cells in order:

jupyter notebook "Pandemic Conditions and Their Influence on Crime Rates in Boston Neighborhoods.ipynb"


## Data Sources

The crime data used in this analysis is from the Boston Police Department's crime incident reports.

## Interactive Visualizations

This analysis includes several interactive visualizations created using Folium. These are exported as HTML files:

- `marker_cluster_2018.html`: Clustered map of crime incidents in 2018
- `marker_cluster_2020.html`: Clustered map of crime incidents in 2020
- `marker_cluster_2022.html`: Clustered map of crime incidents in 2022
- `marker_cluster_neighborhood2018.html`: Neighborhood-level crime map for 2018
- `marker_cluster_neighborhood2020.html`: Neighborhood-level crime map for 2020
- `marker_cluster_neighborhood2022.html`: Neighborhood-level crime map for 2022

These HTML files can be opened in a web browser to interact with the visualizations directly.
