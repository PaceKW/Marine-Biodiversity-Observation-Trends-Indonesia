# Marine Biodiversity Observation Trends & Sea Surface Temperature –  Indonesia (2015 – 2025)

## Project Overview

This project explores temporal and spatial patterns in marine biodiversity observation records and examines their association with regional sea surface temperature (SST) trends in Indonesian waters between 2015 and 2025.

The analysis emphasizes responsible use of large-scale marine datasets, focusing on data aggregation, exploratory visualization, and transparent interpretation rather than detailed ecological modeling.

---

## Objectives

- Aggregate marine biodiversity observation records into annual trends  
- Analyze regional annual sea surface temperature patterns  
- Explore temporal associations between biodiversity observations and SST  
- Visualize spatial distribution of marine biodiversity observation records  
- Communicate findings with clear scientific limitations  

---

## Datasets

### 1. Marine Biodiversity Data (OBIS)

- **Source:** Ocean Biodiversity Information System (OBIS)  
- **Website:** https://obis.org  
- **Region:** Indonesia  
- **Period:** 2015–2025  
- **Data type:** Marine species occurrence records  

In this project, OBIS data were used to:
- Extract observation dates (`eventDate`) for annual aggregation  
- Visualize spatial distribution using geographic coordinates (`decimalLatitude`, `decimalLongitude`)  

No species-level ecological inference, habitat modeling, or abundance estimation was performed. Observation counts represent recorded occurrences and are influenced by sampling effort and data availability.

---

### 2. Sea Surface Temperature (SST)

- **Source:** National Oceanic and Atmospheric Administration (NOAA)  
- **Product:** Optimum Interpolation Sea Surface Temperature (OISST)  
- **Website:** https://www.ncei.noaa.gov/products/optimum-interpolation-sst  
- **Data type:** Sea surface temperature time series  

Sea surface temperature data were processed to:
- Convert timestamps to calendar years  
- Aggregate SST values into annual regional mean temperatures  

Spatially explicit matching between SST grids and individual biodiversity observations was outside the scope of this analysis.

---

## Scope of Analysis

This project focuses on high-level temporal and spatial exploration using selected fields from large marine datasets. The objective is to demonstrate practical experience working with real-world marine biodiversity and environmental data while avoiding overinterpretation.

The analysis emphasizes:
- Data cleaning and temporal aggregation  
- Exploratory trend analysis  
- Spatial visualization of observation density  
- Transparent discussion of data limitations  

---

## Methodology

### Data Preparation
1. Cleaned and parsed OBIS observation dates  
2. Aggregated biodiversity records into annual observation counts  
3. Processed SST data into annual mean regional values  

### Analysis
- Temporal trend visualization  
- Correlation analysis between annual observation counts and SST  
- Spatial density mapping of biodiversity observation records  

---

## Key Visualizations

- Annual marine biodiversity observation trends  
- Annual mean sea surface temperature trends  
- Combined trend comparison plots  
- Spatial distribution and density of marine biodiversity observations  

---

## Key Findings

- Marine biodiversity observation records show interannual variability between 2015 and 2025.  
- Annual mean sea surface temperature exhibits observable temporal trends.  
- A temporal association between observation counts and SST trends is present; however, this does not imply causation.

Observed patterns likely reflect a combination of environmental variability, research activity, and sampling effort.

---

## Limitations

- OBIS data represent observation records, not true species abundance.  
- Observation density is influenced by survey effort and accessibility.  
- Annual SST aggregation masks seasonal and short-term variability.  
- Additional environmental parameters were not included.

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook (Kaggle)  
- Open marine biodiversity and environmental datasets  

---

## Author

**Henry Kevin**  
Background: Information Systems | Data Science | Machine Learning  
Focus: Environmental Data Analysis & Marine Biodiversity

_Notes: This analysis reflects a junior-level, research-oriented data exploration with an emphasis on responsible interpretation and scientific transparency._