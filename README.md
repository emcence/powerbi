# Powerbi assignemnt
PowerBI report for task assignment

## Files included
- Spredsheets containing data 
- Power point containing dahsboards from the report and all screenshots from the pbix file mentioned further down
- PBIX file 

## Data import
Attached files from the task assignment are imported. During the import invalid columns containg **Error**, **Duplicate records** are removed. After cleaning data is imported into tables.

## Data model creation
Loaded tables are connected via relations **1 to many**. According to the assignment additional metricas are created: **ForecastPerWeek**, **Stock level**, **Weeks in stock**. Those metrics are needed to create visualisations. 

## Visualisation
- Two Cards visualisations are created:
  - **Stock Level** showing total stocks
  - **Weeks in Stock** showing average weeks in stock
- Bar/Column Chart is added which are showing **Product category** and **Purchasing Manager** versus Stock Level
- Slicers are added that allow filtering per **Warehouse**, **Purchasing Manager** and **Product Category**

## Formating
Default formating is taken due to lack of time


