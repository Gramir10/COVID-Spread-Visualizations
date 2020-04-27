# COVID-Spread-Visualizations

## Business Question
How can the spread of the COVID-19 pandemic in the US be tracked, and which areas require assistance?

## Data Question
Plotly express is used to build an animated choropleth map of which areas are most heavily afflicted by the virus, accounting for the capacity of hospital beds per area.

## Data Answer

After cleaning the data and merging the data sets by FIPS code, a bubble map, density map, and choropleth map were created (which are displayed here). 

![alt text](https://github.com/Gramir10/COVID-Spread-Visualizations/blob/master/bubble_map.png)
</br>shows the distribution of COVID-19 cases
![alt text](https://github.com/Gramir10/COVID-Spread-Visualizations/blob/master/CovidSpread.gif)
</br>shows the spread of COVID-19 cases
![alt text](https://github.com/Gramir10/COVID-Spread-Visualizations/blob/master/HospitalBeds.gif)
</br>shows which areas are getting overwhelmed in hospital bed capacity by COVID-19 cases

## Business Answer
Based on the COVID-19 Cases in the US Counties Per Hospital Beds, we can see some small rural counties do not have the hospital capacity to take care of their sick. Mobilizing resources to move the infected or set up field hospitals would be advised. The intial spread hit the cities first, but quickly spread to the countryside. As the infections clear in the cities, COVID will likely persist in the rural areas for some time. Additional testing resources should be sent to VA, TX, and Wyoming, which are lacking in data. 

# Data Sources

[JHU COVID-19 Data](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports/04-14-2020.csv)

[US Census Population Data](https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/co-est2019-alldata.csv)

[New York Times Data](https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties.csv)


[Homeland Infrastructure Foundation-Level](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals)
 </br>
Where hospital bed data was retrieved.
