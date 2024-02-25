# Visualizing Civic Engagement - City of Bloomington

This repository contains code and visualizations for the "Visualizing Civic Engagement - City of Bloomington" final project for the Fall 2023 Data Visualization course at Indiana University. 

## Project Overview

The goal of this project is to analyze and visualize civic engagement data for the city of Bloomington, Indiana using the comprehensive Open311 dataset. Through interactive data visualizations, we aim to uncover patterns, trends, and insights into civic requests and responses to inform urban planning and community engagement.

## Data

The primary dataset used is the Open311 data from the city of Bloomington portal. This contains details on resident service requests, including:

- Request category 
- Submission date
- Resolution time
- Status  
- Responsible agency
- Location coordinates

The raw data was preprocessed to handle missing values, format inconsistencies, and create additional fields for temporal analysis.

## Methodology

The project methodology involves:

- **Geospatial analysis** using Geopandas and Folium to map service request distribution
- **Interactive visualizations** with Plotly dashboards to enable filtering and exploration
- **Visualizations** using treemaps, animated charts, and scatter plots to analyze request volumes, agency activity, temporal patterns, and location data

## Visualizations

The key visualizations developed include:

- Treemap showing top requested services by year
- Animated bar chart of top agencies by year 
- Scatter plot analyzing seasonal patterns in top service requests
- Folium cluster map of request locations
- Choropleth map of requests by ZIP code
- Interactive dashboard of open requests by agency

## Usage

The source code for data collection, preprocessing, analysis, and visualization is provided in the `src` folder. Visualizations are saved as HTML files in the `vis` folder. 

To run the analysis and rebuild the visualizations:

1. Clone the repository 
2. Ensure the required packages are installed
3. Run the Jupyter notebooks.

This project was completed as part of the Fall 2023 Data Visualization course at Indiana University.
