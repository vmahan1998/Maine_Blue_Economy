# Health of fish stocks by region - Data package

This data package contains the data that powers the chart ["Health of fish stocks by region"](https://ourworldindata.org/grapher/biomass-fish-stocks-region?country=~US+Northeast+Coast&v=1&csvType=filtered&useColumnShortNames=false) on the Our World in Data website. It was downloaded on March 14, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:
country: , US Northeast Coast

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


## biomass_mean_region


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
RAM Legacy Database; Hilborn,et al. (2020). Effective fisheries management instrumental in improving fish stock status. – processed by Our World in Data

#### Full citation
RAM Legacy Database; Hilborn,et al. (2020). Effective fisheries management instrumental in improving fish stock status. – processed by Our World in Data. “biomass_mean_region” [dataset]. RAM Legacy Database; Hilborn,et al. (2020). Effective fisheries management instrumental in improving fish stock status. [original data].
Source: RAM Legacy Database; Hilborn,et al. (2020). Effective fisheries management instrumental in improving fish stock status. – processed by Our World In Data

### Additional information about this data
This dataset provides aggregated data on fish biomass, fishing pressure and catch by region and taxa, based on the results of the RAM Legacy Stock Assessment Database: https://www.ramlegacy.org/

This aggregated data was provided by Michael Melnychuk, researcher on the RAM Legacy Database.

These results were published in PNAS here:
Hilborn, R., Amoroso, R. O., Anderson, C. M., Baum, J. K., Branch, T. A., Costello, C., ... & Ye, Y. (2020). Effective fisheries management instrumental in improving fish stock status. Proceedings of the National Academy of Sciences, 117(4), 2218-2224. Available at: https://www.pnas.org/content/117/4/2218

Definitions are as follows:
– 'Biomass' is a measure of biomass of fish divided by the biomass of fish at the maximum sustainable yield (B / Bmsy)
– 'Fishing pressure' is a measure of fishing pressure divided by the pressure at the maximum sustainable yield (U / Umsy)
– 'Catch' is a measure of the annual catch divided by the mean catch across the stock's time series


    