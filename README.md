# US Accidents Data Analysis and Visualization

## Overview

This repository contains Python-based analysis and visualizations of **US Accidents** data to identify patterns, trends, and insights related to accidents across various regions and timeframes. The project uses various libraries such as **Pandas**, **Seaborn**, **Matplotlib**, **Folium**, and others to process and visualize accident data effectively.

The primary focus of this project is to:

1. Perform **Exploratory Data Analysis (EDA)** to understand the underlying data.
2. Investigate **accidents per capita** by state and visualize it.
3. Analyze trends based on **start time**, **city**, **latitude/longitude**, and other relevant factors.
4. Create interactive **heatmaps** to visualize accident distributions using **Folium**.

## Files and Directories

1.US_Accidents_March23.csv - Main dataset containing accident details.
2.us_pop_by_state.csv - Population data by state for accident per capita analysis.
3.EDA_PROJECT.ipynb - Jupyter Notebook containing the entire analysis and visualizations.


## Installation

Ensure that you have **Python 3.x** installed. Use `pip` or `conda` to install the required libraries.

## Dataset Description

### US Accidents Data (March 2023)
- **City**: City where the accident occurred.
- **Start_Time**: Date and time when the accident occurred.
- **Start_Lat**: Latitude where the accident occurred.
- **Start_Lng**: Longitude where the accident occurred.
- **Temperature**: Temperature during the accident.
- **Weather_Condition**: Weather condition at the time of the accident.
- **Source**: Source of the data (e.g., traffic cameras, sensors).

### US Population Data by State
- **State**: The state code for the US state.
- **2020_Census**: Population of the state as per the 2020 census.

---

## Analysis and Methodology

### 1. Data Cleaning
The dataset was cleaned by:
- Checking for missing values and removing columns with excessive missing data.
- Identifying and keeping columns relevant to the analysis.

### 2. Exploratory Data Analysis (EDA)
Key features explored:
- **City-wise Accident Distribution**: Analyzed cities based on the number of accidents.
- **Time Analysis**: Distribution of accidents by hour of the day, day of the week, month, and year.
- **Weather Conditions**: Investigated how weather impacts the frequency of accidents.

### 3. Accidents Per Capita Analysis
- Merged accident data with **US population data by state**.
- Calculated **accidents per capita** for each state.
- Identified the top 5 states with the highest accidents per capita.

### 4. Geospatial Analysis and Heatmaps
- Created **interactive heatmaps** to visualize accident distribution across the US using **Folium**.
- Analyzed the relationship between latitude and longitude of accidents.

---

## Key Visualizations

### 1. Bar Chart of Cities by Accidents
This bar chart displays the number of accidents in various cities across the US. It helps identify cities with the most significant number of accidents.

<img width="620" alt="Screenshot 2025-02-04 at 1 18 33 AM" src="https://github.com/user-attachments/assets/d817aa99-0f91-4c77-ab36-09665e5a80c7" />


### 2. Heatmaps of Accident Locations
Interactive **Folium Heatmap** visualizing accident density based on geographical locations (latitude and longitude). 

<img width="920" alt="Screenshot 2025-02-04 at 1 15 37 AM" src="https://github.com/user-attachments/assets/5899f1fd-2999-4e7f-8461-1af832526098" />


### 3. Accidents Per Capita by State
Bar plot displaying states sorted by accidents per capita. This provides insights into the states with the highest accident rates relative to their population.

<img width="701" alt="Screenshot 2025-02-04 at 1 20 48 AM" src="https://github.com/user-attachments/assets/a4f868f3-2630-4090-86be-f33e387911cd" />


### 4. Time-based Trends
Distribution plots showing accident trends based on the following:
- **Hour of the Day**: Identifying peak hours for accidents.
- **Day of the Week**: Analyzing how accidents vary between weekdays and weekends.
- **Month of the Year**: Investigating trends by month, such as seasonal effects.

---
# Conclusion

This analysis provides a comprehensive overview of accident trends across the United States. The accidents per capita analysis helps identify states that experience higher rates of accidents relative to their population, while the geospatial heatmaps provide insight into accident density across different regions. The time-based analysis identifies patterns related to the time of day, day of the week, and seasonality of accidents.

## Further Enhancements

1.Incorporating additional weather data to analyze its direct impact on accidents.
2.Using machine learning techniques to predict accident hotspots and times.
3.Exploring other factors such as road type, traffic volume, and infrastructure.



