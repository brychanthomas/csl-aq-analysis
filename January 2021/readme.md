# January 2021

In January the air quality monitor had to be taken down for repairs and upgrades
needed for compatibility with the new Things Stack (v3), as it was announced that v2 of the 
Things Network would soon be retired.

These notebooks analyse the data recorded up until that point.

## Notebooks

- weather.ipyndb - Jupyter notebook showing correlations between weather conditions and levels of different pollutants
- time.ipyndb - Jupyter notebook showing trends in the air quality index over different time periods
- aqi-comparison.ipyndb - Jupyter notebook showing the correlation between the daily air quality index in the city centre and in the school
- pollutant-comparison.ipynb - Jupyter notebook that attempts to decide which pollutants are of greatest concern at CSL

## Data sources

- csl_data.csv - Air quality readings recorded by the CSL TTN air quality monitor
- cardiff_centre_data.csv - Air quality readings recorded by an air quality monitor in Cathays, downloaded from the [Department for Environment, Food and Rural Affairs](https://uk-air.defra.gov.uk/data/data_selector_service)
- cardiff_centre_AQI.csv - Air Quality Index measurements calculated using the data from the air quality monitor in Cathays by the [World Air Quality Index Project](https://aqicn.org/data-platform/register/)
