---
output:
  
  html_document: default
  pdf_document: default
---
# STAT 5710 - Group 51 Project Proposal 

- Jenea Adams 
- Annan Timon


## Gentrification and Health Disparities: An Integrated Analysis of Inequality in Philadelphia

## Abstract
Gentrification is a process of affluent residents and businesses displacing existing low-income residents and businesses. Beyond prospects for so-called "urban renewal", gentrification has real, tangible effects on the landscape and trajectories of existing communities who often don't benefit from the changes of a neighborhood and are disenfranchised from participating in the growth of their area. Gentrification also has documented health effects on communities, such as shortened life expectancy, higher cancer rates, higher infant mortality, and cardiovascular diseases. Income inequality can be used to estimate gentrification rates. It can be quantified by a [Gini index](https://www.census.gov/topics/income-poverty/income-inequality/about/metrics/gini-index.html) which is a value from 0 to 1 indicating inequality in the dispersion of income in a given unit. This study begins to to investigate a statistical framework for capturing the relationship between income inequality and health effects in Philadelphia from integrated datasets. 

## Goal of the study
The goal of the study is to quantify gentrification in Philly's neighborhoods and understand it's perceived effect on public health correlates. We will do this through modeling the relationship of Philadelphia health data and dynamic neighborhood demographics with census tract-level Gini index. 

## Brief discussion about the data

We are aggregating several datasets for this analysis: 

- **Food access**: The Neighborhood Food Retail dataset includes GEOID level assessments of food access relevant to distance and types of high produce grocery stores, as well as if that area is a high poverty area. We chose this to understand the livability of certain areas with respect to their access to fresh food options, which have positive impacts on health. 

- **Hospital locations**: locations of hospitals by type of care provided. We chose this to understand the distribution and access to healthcare in each census block. 

- **Heat Vulnerability**: scores and indicators for heat vulnerability by census block and prevalence of heat-related illnesses. This may or may not be related to access to green space and tree canopy. This data gives us an idea of environmental variables which contribute to health outcomes and quality of life for Philadelphia residents. 

- **Affordable Housing**: locations of affordable and accessible housing projects recorded by the city. This data will provide information on the distribution of affordable housing options mapped to census blocks. 

- **Philadelphia population metrics**: Demographic information of Philadelphia census blocks by race and ethnicity

- **Socioeconomic data** - income inequality calculated as a census tract-level Gini index. 

- **[Health data](https://chronicdata.cdc.gov/500-Cities-Places/500-Cities-Census-Tract-level-Data-GIS-Friendly-Fo/k86t-wghb)**: measures of prevalence of health measures such as cancer prevalence, access to health insurance, blood pressure, heart disease, and more by census tract. 



## Methods to be used

1. Linear Model 
2. Generalized Linear Model + LASSO 
3. Neural Network 


## References 

[Social Explorer](https://www.socialexplorer.com/home)

[censusxy](https://doi.org/10.1111/tgis.12741)

[Gini index](https://www.census.gov/topics/income-poverty/income-inequality/about/metrics/gini-index.html)

[500 Cities Census Tract-level Health Data](https://chronicdata.cdc.gov/500-Cities-Places/500-Cities-Census-Tract-level-Data-GIS-Friendly-Fo/k86t-wghb)

[CDC Gentrification and Health Effects](https://www.cdc.gov/healthyplaces/healthtopics/gentrification.htm#:~:text=Gentrification%20is%20a%20housing%2C%20economic,in%20previously%20run%2Ddown%20neighborhoods.)

[Census block vs census tract (US Census Bureau)](https://uscensusbureau.github.io/citysdk/guides/intro/3/)

![](https://uscensusbureau.github.io/citysdk/assets/images/block.jpg)

