# CAPSTONE DEMO README

### Describe your project (big idea)
Using historical satellite data that monitors various changes in forests, this project aims to analyze forest changes primarily through carbon fluctuations along with tree cover density among different areas of the world. Many of these factors have been known to have a relationship with deforestation thus the project aims to identify patterns within this data and how well these variables perform in predictive power.

### Describe your goal
The goal is to develop a model that can predict potential areas at risk for deforestation based on carbon emissions and tree cover changes.

### Describe your data
The main datasets that I currently have are on carbon data by country and tree cover loss by country. The tree cover dataset includes Hectares of tree cover loss at a national level between 2001-2023, categorized by percent canopy cover in 2000. For the carbon dataset, it includes aboveground woody biomass stocks and densities in 2000 (Mg AGB and Mg AGB/ha, respectively); average annual GHG emissions, removals (sequestration), and net flux between 2001 and 2023 (Mg CO2e/yr); and annual GHG emissions (Mg CO2e) provided by percent canopy cover in 2000 (>30%, 50%, and 75% only). The main data was retrieved from a global forest watch organisation that uses dashboards and interactive maps that take on real-time data.

### Describe your work (models, analysis, EDA, etc.)
The EDA had a few graphs, “Top 5 Countries with Highest Carbon Emissions in 2023” which showed that Brazil followed by US and Canada were the highest contributors likely due to amazon deforestation and oil industry activity. The “Total Tree Canopy Loss between 2001-2023” also showed a mild positive relationship between canopy loss and year (time).
There is also a large number of null values within the carbon data due to the thresholds of 30 and under being non-existent.

### Describe your results
Since we can see gradual canopy loss, we can theorize and hypothesise that higher threshold (denser forests) suffer from great canopy loss overtime. We can also contextualize possible events that may have happened in the 2015-2016 timeframe such as influx of illegal logging events or policy changes Some feature engineering opportunities could involve year-over-year change or possible rolling averages. Other features could include additional datasets like climate(temperature) as there are many variables that affect deforestation

### EDA Findings
Most carbon is stored in primary forests which are areas that are most of interest for logging. Carbon emissions and Tree cover are very positively correlated. Tree Cover loss sporadicness has increased over time and can be explained through changes within this topic space  like wildfires
