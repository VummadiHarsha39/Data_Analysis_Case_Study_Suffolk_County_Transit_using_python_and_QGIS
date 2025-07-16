# Suffolk_County_Transit_Data_Analysis_using_GIS_and_Python

**A Comprehensive Case Study: Transit Performance, Route Analysis, and Socioeconomic Impact in Suffolk County, NY.**

![SCT Logo](Images/sctlogo.png)
---

## 📄 Overview

This project presents an in-depth data analysis case study of Suffolk County Transit (SCT). Driven by personal observations of SCT's punctuality and extensive coverage as a daily commuter, this work assesses the agency's effectiveness in serving Suffolk County, recognized as the largest easternmost county in the USA.

The comprehensive analysis is structured into three distinct phases:

### 1. Bus Ridership Demographics (2013-2016)

This initial phase explores bus ridership trends and patterns between 2013 and 2016. Using data from opendata.suffolk, the analysis involved:
* Loading raw ridership data.
* Creating a 'Date' column for time-series analysis.
* Calculating 'Total_Ridership' by summing various fare types.
* Generating visualizations to illustrate total monthly ridership fluctuations and the overall distribution of ridership by fare type.

### 2. SCT Performance Measures and Operational Characteristics (2013-2023)

The second part focuses on evaluating SCT's efficiency, productivity, and fleet health over a longer period, from 2013 to 2023. Data was sourced from the Federal Transit Administration (FTA) Annual Agency Profiles. Key analytical steps included:
* Cleaning and preparing numerical operational data.
* Calculating essential performance indicators such as 'Operating Expense per Vehicle Revenue Mile'.
* Visualizing trends in these KPIs along with year-over-year changes in operational metrics and fleet characteristics.

### 3. SCT Bus Route Analysis, GIS Visualization, and Social Demographic Impact

This final and most central part of the project links SCT bus routes to crucial demographic data, particularly focusing on poverty. This phase involved:
* Integrating bus stops and route shapes from GTFS data.
* Incorporating town and hamlet polygons for local administrative context.
* Adding census tracts as foundational spatial units.
* Utilizing Python to join population and poverty attributes from American Community Survey (ACS) data with census tracts.
* Creating choropleth maps to visualize the distribution of poverty rates.
* Developing dot density maps to illustrate population and poverty concentrations, with poverty distinctly highlighted in red.
* Generating buffer zones around bus routes to visually represent service corridors.
* Performing demographic overlays to understand the spatial relationship between bus infrastructure and socioeconomic characteristics.

## 📊 Key Visualizations

Here's an example of the GIS visualization integrating SCT routes with demographic overlays:

![QGIS Visualization of Suffolk County Map with SCT and Demographic Overlay](Images/map.png)

## 💡 Key Findings

Ultimately, our analysis confirmed that Suffolk County Transit effectively provides service coverage within Suffolk, the region's largest easternmost county—a finding both curiously insightful and thankfully reassuring.

## 🔗 Full Project Details

For a deeper dive into the methodology, detailed code, and complete analysis, please visit my Medium article:

[Summer Project 1: Analyzing Suffolk County Transit with QGIS & Python](https://medium.com/@vummadiharsha123/summer-project-1-analyzing-suffolk-county-transit-with-qgis-python-9482692bbb80)

---
