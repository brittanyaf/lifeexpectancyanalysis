# Life Expectancy Analysis
## The Data
The Life Expectancy Analysis explores relationships between life expectancy and several factors, such as education level, infant deaths, and adult mortality rates.  The project explores life expectancy globally and within the United States from 2000-2015.  The data used comes from the World Health Organization and was acquired from https://www.kaggle.com/kumarajarshi/life-expectancy-who

## The Analysis
A predictive analysis was conducted to predict life expectancy from 2016-2020.  Analyses conducted in Python (not all are present in the Tableau storyboard): geospatial analysis, regression analysis, time-series analysis, cluster analysis.

## Data Cleaning Process
Cleaning procedures conducted include using Python to look for duplicates, missing values.  There were no duplicate values, however, there were missing values in the Life Expectancy, Adult Mortality, Alcohol, Income composition of resources, and Schooling columns.  Imputation was used to replace Null values with Mean values in those columns.  The life_data dataframe and world dataframe (shapefile) were merged to conduct geospacial analysis.  When merging, column names with country were changed to be consistent with one another.  Additionally, some country names were changed to be consistent (example: Republic of Congo changed to Congo).

## Research Questions
What affects life expectancy the most? What countries have the highest/lowest life expectancy? What factors contribute to life expectancy? Does life expectancy change over time? 

## Tableau Storyboard
[Tableau storyboard](https://public.tableau.com/profile/brittany.anderson.freese#!/vizhome/LifeExpectancyDataAnalysis/LifeExpectancyStoryboard) shows life expectancy results globally, predictive analyses, and contributing factors.  The storyboard includes findings, limitations, and next steps.
