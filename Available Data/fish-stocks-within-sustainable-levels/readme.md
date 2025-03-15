# Status of the world's fish stocks - Data package

This data package contains the data that powers the chart ["Status of the world's fish stocks"](https://ourworldindata.org/grapher/fish-stocks-within-sustainable-levels?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Biologically sustainable
Fish stock are subpopulations of a particular species of fish which have common parameters such as location, growth and mortality which define their population dynamics. Fish stocks are within biologically sustainable levels when fish catch does not exceed the maximum sustainable yield (MSY) - the rate at which fish populations can regenerate.

Last updated: March 14, 2024  
Next update: April 2025  
Date range: 1974–2019  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data. “Biologically sustainable – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “SDG Indicators: SDG Indicators” [original data].
Source: Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World In Data

### Source

#### Food and Agriculture Organization of the United Nations – SDG Indicators: SDG Indicators
Retrieved on: 2024-03-14  
Retrieved from: http://www.fao.org/faostat/en/#data/SDGB  


## Overexploited
Fish stock are subpopulations of a particular species of fish which have common parameters such as location, growth and mortality which define their population dynamics. Fish stocks are overexploited when fish catch exceeds the maximum sustainable yield (MSY) - the rate at which fish populations can regenerate.

Last updated: March 14, 2024  
Next update: April 2025  
Date range: 1974–2019  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World in Data. “Overexploited – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “SDG Indicators: SDG Indicators” [original data].
Source: Food and Agriculture Organization of the United Nations (2023) – with major processing by Our World In Data

### Source

#### Food and Agriculture Organization of the United Nations – SDG Indicators: SDG Indicators
Retrieved on: 2024-03-14  
Retrieved from: http://www.fao.org/faostat/en/#data/SDGB  


    