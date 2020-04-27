# COVID-Spread-Visualizations

![alt text](https://github.com/Gramir10/COVID-Spread-Visualizations/blob/master/bubble_map.png)
shows the distribution of COVID-19 cases
![alt text](https://github.com/Gramir10/COVID-Spread-Visualizations/blob/master/CovidSpread.gif)
shows the spread of COVID-19 cases
![alt text](https://github.com/Gramir10/COVID-Spread-Visualizations/blob/master/HospitalBeds.gif)
shows which areas are getting overwhelmed in hospital bed capacity by COVID-19 cases
## Business Question
How can we visualize and better understand the overall toll of the COVID-19 pandemic on US counties or county equivalents?

## Data Question
Which data and metrics can we use to answer our question? We'll use plotly express to build an animated choropleth map that shows the number of cumulative confirmed COVID-19 cases per 1,000 residents in US counties, but first, we'll review some geospatial data analysis in Python by making a bubble map and a density heat map to showcase the number of cumulative COVID-19 confirmed cases in each US county on today's date.
We'll use data from the following sources for our analysis:

## Data Answer

The steps for our data analysis are available in this GitBook tutorial. You can use this pre-commented starter notebook to follow along with the tutorial, or copy and paste the code from the codeblocks (dark blue text boxes) in the tutorial to create this and other geospatial data visualizations:

## Business Answer
How might our data visualizations help county and state leadership or business owners in the US? What other data might we want to incorporate into an animated choropleth map to better understand the toll of the novel coronavirus in the United States?

# Data Sources

[JHU COVID-19 Data](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_daily_reports/04-14-2020.csv)

[US Census Population Data](https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/co-est2019-alldata.csv)

[New York Times Data](https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties.csv)


[Homeland Infrastructure Foundation-Level](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals)
 </br>
Where hospital bed data was retrieved.
