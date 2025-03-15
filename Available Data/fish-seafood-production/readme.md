# Fish and seafood production - Data package

This data package contains the data that powers the chart ["Fish and seafood production"](https://ourworldindata.org/grapher/fish-seafood-production?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on March 14, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Production of fish and seafood – FAO
Last updated: March 14, 2024  
Next update: April 2025  
Date range: 1961–2021  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data. “Production of fish and seafood – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “Food Balances: Food Balances (-2013, old methodology and population)”; Food and Agriculture Organization of the United Nations, “Food Balances: Food Balances (2010-)” [original data].
Source: Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World In Data

### How is this data described by its producer - Food and Agriculture Organization of the United Nations (2023)?
Item: Fish and seafood

Metric: Production
Description: Figures relate to the total domestic production whether inside or outside the agricultural sector, i.e. it includes non-commercial production and production from kitchen gardens. Unless otherwise indicated, production is reported at the farm level for crop and livestock products (i.e. in the case of crops, excluding harvesting losses) and in terms of live weight for fish items (i.e. the actual ex-water weight at the time of the catch). All data shown relate to total meat production from both commercial and farm slaughter. Data are expressed in terms of dressed carcass weight, excluding offal and slaughter fats. Production of beef and buffalo meat includes veal; mutton and goat meat includes meat from lambs and kids; pig meat includes bacon and ham in fresh equivalent. Poultry meat includes meat from all domestic birds and refers, wherever possible, to ready-to-cook weight. Source: FAO Statistics Division

### Sources

#### Food and Agriculture Organization of the United Nations – Food Balances: Food Balances (-2013, old methodology and population)
Retrieved on: 2024-03-14  
Retrieved from: http://www.fao.org/faostat/en/#data/FBSH  

#### Food and Agriculture Organization of the United Nations – Food Balances: Food Balances (2010-)
Retrieved on: 2024-03-14  
Retrieved from: http://www.fao.org/faostat/en/#data/FBS  


    