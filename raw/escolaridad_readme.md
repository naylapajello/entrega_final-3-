# Expected years of schooling among children - Data package

This data package contains the data that powers the chart ["Expected years of schooling among children"](https://ourworldindata.org/grapher/years-of-schooling?v=1&csvType=full&useColumnShortNames=false&level=all&metric_type=expected_years_schooling&sex=both) on the Our World in Data website. It was downloaded on June 21, 2026.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For most countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.


## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Expected years of schooling – UNDP
Number of years a child of school-entrance-age can expect to receive if the current age-specific enrollment rates persist throughout the child's life.
Last updated: May 7, 2025  
Next update: July 2026  
Date range: 1990–2023  
Unit: years  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
UNDP, Human Development Report (2025) – with minor processing by Our World in Data

#### Full citation
UNDP, Human Development Report (2025) – with minor processing by Our World in Data. “Expected years of schooling – UNDP” [dataset]. UNDP, Human Development Report, “Human Development Report” [original data].
Source: UNDP, Human Development Report (2025) – with minor processing by Our World In Data

### What you should know about this data
* This indicator shows how many years a student starting school in that year is expected to spend in education.  It's based on the enrollment patterns observed in that country in that specific year.
* The calculation looks at how many students are enrolled at each age and education level, then estimates how long a new student would stay in school if those patterns continued. This includes time spent repeating grades, not just the official length of each school level.
* It measures participation in schooling - how long students are likely to stay in school - rather than whether they actually learn or graduate.
* Higher numbers mean students spend more years in school, either because the official school system is longer or because many students repeat grades.
* UNDP originally obtained this indicator from: ICF Macro Demographic and Health Surveys (various years), UNESCO Institute for Statistics (2024) and United Nations Children's Fund (UNICEF) Multiple Indicator Cluster Surveys (various years).

### Source

#### UNDP, Human Development Report – Human Development Report
Retrieved on: 2025-05-07  
Retrieved from: https://hdr.undp.org/  


    