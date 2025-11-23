# An Analysis of Crime in Milwaukee

### 📊 Project Overview
This project leverages **Geospatial Data Science** to analyze historical crime trends in Milwaukee. The primary focus was to process WIBR (Wisconsin Incident-Based Reporting) datasets to map high-risk zones and aid in predictive resource allocation.

### 🔍 Methodologies
* **Geospatial Mapping:** Utilized `GeoPandas` to visualize Milwaukee's ALD Districts and Strategic Planning Areas.
* **Density Analysis:** Generated heat maps to visualize the spatial distribution of incident frequency.
* **Data Cleaning:** Processed raw incident reports to standardize coordinate data for plotting.

### 🗺️ Spatial Analysis & Visualization
The analysis generated choropleth maps to identify "hot spots" and statistically significant clusters of criminal activity across the city districts.

<img width="891" height="416" alt="Screenshot 2025-11-22 at 8 56 38 PM" src="https://github.com/user-attachments/assets/45e5b1f1-4818-4f6b-98d3-6d9329b33057" />


### 📈 Key Insights
The spatial analysis reveals that crime incidents are not uniformly distributed but are clustered in specific ALD districts. These visualizations provide a data-driven basis for targeted resource deployment.

### 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=geopandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-013243?style=flat-square&logo=matplotlib&logoColor=white)

### 📂 Repository Contents
* **0 data science project-geo.ipynb**: The geospatial analysis notebook containing coordinate mapping logic.
* **Data Science Project.ipynb**: Data cleaning and preprocessing scripts.
* **Project-Report_final.pdf**: Full project findings and executive summary.
* **wibr.csv**: The dataset used for analysis.
