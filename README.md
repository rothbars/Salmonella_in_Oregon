# Seth Rothbard
## Exploration of the Spatial and Social Distribution of *Salmonella* infections in Oregon.

## Project Proposal
The objective of this project is to perform spatial cluster analysis of lab-
confirmed Salmonella in Oregon counties for the years 2008-2017 for which county
level data are available and create an interactive web map to describe the data.
Also, this data will be combined with county-level Social Vulnerability Index (SVI) data from the CDC
in order to explore associations of Salmonella infections in Oregon
with sociodemographic risk factors. My goal is to be able to toggle different variables on/off
so that the user could see the spatial patterns of *Salmonella* infections by different risk factors.

**I want the project to address these questions:**
1. Which counties in Oregon show an increasing trend in
lab-confirmed Salmonella infections over time?
2. Are there clusters of counties in
Oregon with higher than expected Salmonella infections compared to what is
expected in the state? Where are they?
3. How are the counties with higher
incidences of Salmonella infections related to variables associated with
increased social vulnerability?

| Data                                | Description                                                                                                                             | URL Link                                                                                                                       | Memo                                                                                                                                                                                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ore_counties                        | Shapefile of Oregon county boundaries                                                                                                   | https://github.com/jakobzhao/geog571/tree/master/lectures/lec11/assets                                                         | Asset table data will be merged with this shapefile data based on  county name.                                                                                                                                                                              |
| Salmonella                          | De-identified data set of lab-confirmed Salmonella infections in Oregon from 2008-2017. Locations were aggregated to the county level.  | Not publicly available due to confidentiality concerns. Data were collected  and de-identified by the Oregon Health Authority. | Includes information regarding specific type of Salmonella infections and disease onset dates.                                                                                                                                                               |
| Population                          | Yearly population estimates for Oregon counties from 2008-2017 gathered by the Population Research Center at Portland State University. | https://www.pdx.edu/prc/population-reports-estimates                                                                           | Number of infections will be divided by population estimates to calculate infection rates (for example number of confirmed Salmonella cases per 10,000 people). Rates are  generally preferred over disease counts as an accurate measure of disease burden. |
| Vulnerability_Index_Oregon (2016)   | Based on US census data in 2016 this is a dataset which contains 15 measures related to social vulnerability for all Oregon counties.   | https://svi.cdc.gov/data-and-tools-download.html                                                                               | Variables include: socioeconomic status, race/ethnicity/language, housing composition, transportation, etc.                                                                                                                                                  |
| Public Health Image Library  (PHIL) | Library of (mostly) copyright cleared images related to various public health topics.                                                   | https://phil.cdc.gov/                                                                                                          | Will be used to gather images to make my website more aesthetically appealing/aid in user comprehension of my topic.                                                                                                                                         |
