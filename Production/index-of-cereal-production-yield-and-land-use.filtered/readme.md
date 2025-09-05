# Change in cereal production, yield, land use and population - Data package

This data package contains the data that powers the chart ["Change in cereal production, yield, land use and population"](https://ourworldindata.org/grapher/index-of-cereal-production-yield-and-land-use?country=~IND&v=1&csvType=filtered&useColumnShortNames=false) on the Our World in Data website.

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


## Land used for cereal production – FAO
Cereals include wheat, rice, maize, barley, oats, rye, millet, sorghum, buckwheat, and mixed grains.
Last updated: March 17, 2025  
Next update: March 2026  
Date range: 1961–2023  
Unit: hectares  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data. “Land used for cereal production – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “Production: Crops and livestock products” [original data].
Source: Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World In Data

### How is this data described by its producer - Food and Agriculture Organization of the United Nations (2025)?
Item: Cereals, primary

Description: Cereals are generally of the gramineous family and, in the FAO concept, refer to crops harvested for dry grain only. Crops harvested green for forage, silage or grazingare classified as fodder crops. Also excluded are industrial crops, e.g. broom sorghum (Crude organic materials nes) and sweet sorghum when grown for syrup (Sugar crops nes). For international trade classifications, fresh cereals (other than sweet corn), whether or not suitable for use as fresh vegetables, are classified as cereals. Cereals are identified according to their genus. However, when two or more genera are sown and harvested as a mixture they should be classified and reported as "mixed grains". Production data are reported in terms of clean, dry weight of grains (12-14 percent moisture) in the form usually marketed. Rice, however, is reported in terms of paddy. Apart from moisture content and inedible substances such as cellulose, cereal grains contain, along with traces of minerals and vitamins, carbohydrates - mainly starches - (comprising 65-75 percent of their total weight), as well as proteins (6-12 percent) and fat (1-5 percent). The FAO definitions cover 17 primary cereals, of which one - white maize - is a component of maize. Each definition is listed along with its code, botanical name or names, and a short description. Cereal products derive either from the processing of grain through one or more mechanical or chemical operations, or from the processing of flour, meal or starch. Each cereal product is listed after the cereal from which it is derived.

Metric: Area harvested

Description: Area from which a crop is gathered. Area harvested, therefore, excludes the area from which, although sown or planted, there was no harvest due to damage, failure, etc. It is usually net for temporary crops and some times gross for permanent crops. Net area differs from gross area insofar as the latter includes uncultivated patches, footpaths, ditches, headlands, shoulders, shelterbelts, etc. If the crop under consideration is harvested more than once during the year as a consequence of successive cropping (i.e. the same crop is sown or planted more than once in the same field during the year), the area is counted as many times as harvested. On the contrary, area harvested will be recorded only once in the case of successive gathering of the crop during the year from the same standing crops. With regard to mixed and associated crops, the area sown relating to each crop should be reported separately. When the mixture refers to particular crops, generally grains, it is recommended to treat the mixture as if it were a single crop; therefore, area sown is recorded only for the crop reported.

### Source

#### Food and Agriculture Organization of the United Nations – Production: Crops and livestock products
Retrieved on: 2025-03-17  
Retrieved from: http://www.fao.org/faostat/en/#data/QCL  


## Cereal production – FAO
Cereals include wheat, rice, maize, barley, oats, rye, millet, sorghum, buckwheat, and mixed grains.
Last updated: March 17, 2025  
Next update: March 2026  
Date range: 1961–2023  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data. “Cereal production – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “Production: Crops and livestock products” [original data].
Source: Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World In Data

### How is this data described by its producer - Food and Agriculture Organization of the United Nations (2025)?
Item: Cereals, primary

Description: Cereals are generally of the gramineous family and, in the FAO concept, refer to crops harvested for dry grain only. Crops harvested green for forage, silage or grazingare classified as fodder crops. Also excluded are industrial crops, e.g. broom sorghum (Crude organic materials nes) and sweet sorghum when grown for syrup (Sugar crops nes). For international trade classifications, fresh cereals (other than sweet corn), whether or not suitable for use as fresh vegetables, are classified as cereals. Cereals are identified according to their genus. However, when two or more genera are sown and harvested as a mixture they should be classified and reported as "mixed grains". Production data are reported in terms of clean, dry weight of grains (12-14 percent moisture) in the form usually marketed. Rice, however, is reported in terms of paddy. Apart from moisture content and inedible substances such as cellulose, cereal grains contain, along with traces of minerals and vitamins, carbohydrates - mainly starches - (comprising 65-75 percent of their total weight), as well as proteins (6-12 percent) and fat (1-5 percent). The FAO definitions cover 17 primary cereals, of which one - white maize - is a component of maize. Each definition is listed along with its code, botanical name or names, and a short description. Cereal products derive either from the processing of grain through one or more mechanical or chemical operations, or from the processing of flour, meal or starch. Each cereal product is listed after the cereal from which it is derived.

Metric: Production

Description: Amount produced in the year.

### Source

#### Food and Agriculture Organization of the United Nations – Production: Crops and livestock products
Retrieved on: 2025-03-17  
Retrieved from: http://www.fao.org/faostat/en/#data/QCL  


## Cereal yields – FAO
Measured in tonnes per hectare.
Last updated: March 17, 2025  
Next update: March 2026  
Date range: 1961–2023  
Unit: tonnes per hectare  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data

#### Full citation
Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World in Data. “Cereal yields – FAO” [dataset]. Food and Agriculture Organization of the United Nations, “Production: Crops and livestock products” [original data].
Source: Food and Agriculture Organization of the United Nations (2025) – with major processing by Our World In Data

### What you should know about this data
* Cereals include wheat, rice, maize, barley, oats, rye, millet, sorghum, buckwheat, and mixed grains.

### How is this data described by its producer - Food and Agriculture Organization of the United Nations (2025)?
Item: Cereals, primary

Description: Cereals are generally of the gramineous family and, in the FAO concept, refer to crops harvested for dry grain only. Crops harvested green for forage, silage or grazingare classified as fodder crops. Also excluded are industrial crops, e.g. broom sorghum (Crude organic materials nes) and sweet sorghum when grown for syrup (Sugar crops nes). For international trade classifications, fresh cereals (other than sweet corn), whether or not suitable for use as fresh vegetables, are classified as cereals. Cereals are identified according to their genus. However, when two or more genera are sown and harvested as a mixture they should be classified and reported as "mixed grains". Production data are reported in terms of clean, dry weight of grains (12-14 percent moisture) in the form usually marketed. Rice, however, is reported in terms of paddy. Apart from moisture content and inedible substances such as cellulose, cereal grains contain, along with traces of minerals and vitamins, carbohydrates - mainly starches - (comprising 65-75 percent of their total weight), as well as proteins (6-12 percent) and fat (1-5 percent). The FAO definitions cover 17 primary cereals, of which one - white maize - is a component of maize. Each definition is listed along with its code, botanical name or names, and a short description. Cereal products derive either from the processing of grain through one or more mechanical or chemical operations, or from the processing of flour, meal or starch. Each cereal product is listed after the cereal from which it is derived.

Metric: Yield

### Source

#### Food and Agriculture Organization of the United Nations – Production: Crops and livestock products
Retrieved on: 2025-03-17  
Retrieved from: http://www.fao.org/faostat/en/#data/QCL  


## Population
Population by country, available from 10,000 BCE to 2023, based on data and estimates from different sources.
Last updated: July 15, 2024  
Next update: July 2026  
Date range: 10000 BCE – 2023 CE  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
HYDE (2023); Gapminder (2022); UN WPP (2024) – with major processing by Our World in Data

#### Full citation
HYDE (2023); Gapminder (2022); UN WPP (2024) – with major processing by Our World in Data. “Population” [dataset]. PBL Netherlands Environmental Assessment Agency, “History Database of the Global Environment 3.3”; Gapminder, “Population v7”; United Nations, “World Population Prospects”; Gapminder, “Systema Globalis” [original data].
Source: HYDE (2023); Gapminder (2022); UN WPP (2024) – with major processing by Our World In Data

### Sources

#### PBL Netherlands Environmental Assessment Agency – History Database of the Global Environment
Retrieved on: 2024-01-02  
Retrieved from: https://doi.org/10.24416/UU01-AEZZIT  

#### Gapminder – Population
Retrieved on: 2023-03-31  
Retrieved from: http://gapm.io/dpop  

#### United Nations – World Population Prospects
Retrieved on: 2024-07-11  
Retrieved from: https://population.un.org/wpp/Download/  

#### Gapminder – Systema Globalis
Retrieved on: 2023-03-31  
Retrieved from: https://github.com/open-numbers/ddf--gapminder--systema_globalis  

#### Notes on our processing step for this indicator
The population data is constructed by combining data from multiple sources:

- 10,000 BCE - 1799: Historical estimates by HYDE (v3.3).

- 1800 - 1949: Historical estimates by Gapminder (v7).

- 1950-2023: Population records by the UN World Population Prospects (2024 revision).


    