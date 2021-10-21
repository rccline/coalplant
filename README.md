**README**  
<br>
This repository examines a list of European coal plants and transmission nodes that meet certain criteria.

The data source for this project comes in part from the [*European Coal Database* (ECD)](https://beyond-coal.eu/database/) maintained by the *Europe Beyond Coal* campaign for the period 2005 to 2019.  This data is used to screen coal plants to identify coal plants with a power capacity greater than 800 MW which have been retired or that are scheduled to be retired in the near future.

Since the ECD database does not contain the CO2 levels which were produced when the retired plants were in operation, a linear model derived using data from German coal plants is used to estimate the plant MW capacity by analyzing the CO2 production from existing plant operations at the threshold of 800 MW. 

The first document in this repository is *coal_database.Rmd* which is an analysis of the ECD data to estimate CO2 levels for lignite and hard coal plants which produce 800 MW of power.  

The second document of this repository will screen the ECD for a list of coal plants that meet the criteria.   