# Introduction
This project focuses on analyzing and visualizing data from the Vélib' self-service bike 🚲 system in Paris. By connecting to real-time data, the project explores the distribution of bike stations, capacities, and availability across Paris. Interactive maps are created using the Folium library to provide a detailed geographic overview.
 # Background
 ### Context
 Vélib' is a public self-service bike-sharing system in Paris, allowing residents and visitors to access bikes from multiple stations across the city.

 ### Problem
 The goal of this project is to analyze the availability and capacity of Vélib' stations in real time. Specifically, the project seeks to:
- Understand station distribution across neighborhoods.
- Visualize station capacities and bike availability.
- Present actionable insights using interactive maps and data aggregation.

 # Tools Used
- **Python**: pandas, matplotlib, seaborn, folium, requests librairies.
- Real-Time Open Data: Vélib' real-time availability dataset.
- Visualization: Interactive maps and statistical charts.
- Visual Studio Code: my go-to for database management and executing SQL queries.

 # The Analysis

 **1. Data Collection:**
- Connected to the Vélib' API to retrieve real-time station data.
- Structured the data into a pandas DataFrame for further analysis.

**2. Station Capacity Analysis:**
- Visualized capacity distribution using histograms and boxplots.
- Explored capacity trends across different Parisian neighborhoods.

**3. Mapping Vélib' Stations**
- Plotted individual stations on a map with details such as station name, location, and capacity.
- Aggregated station data to compute total capacities and availability for each neighborhood.

**4. City-Level Analysis:**
- Calculated the number of stations, total capacity, available bikes, and docks for each neighborhood.
- Displayed the results with interactive markers on a map, centered on each neighborhood.

 # Results

 **Interactive Maps:**
- Station Map: Displays all Vélib' stations in Paris, showing capacity and availability at each location.
- Neighborhood Map: Highlights aggregated stats for each neighborhood, including the number of stations, total capacity, available bikes, and docks.

**Visual Insights:**
- Clear capacity distribution trends across neighborhoods.
- Identification of areas with higher or lower bike availability.

**PLEASE! : Follow this link to see the two interactive maps :**
 https://nbviewer.org/github/BaptisteLazarus/Self-Service-Bikes-Paris-Viz/blob/main/Self_Service_Bikes_Paris.ipynb