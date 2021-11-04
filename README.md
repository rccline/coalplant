**README**  
<br>
This repository examines a list of European coal plants and transmission nodes that meet certain criteria.

The data source for this project comes in part from the [*European Coal Database* (ECD)](https://beyond-coal.eu/database/) maintained by the *Europe Beyond Coal* campaign for the period 2005 to 2020.  This data is used to screen coal plants to identify coal plants with a power capacity greater than 800 MW which have been retired or that are scheduled to be retired in the near future.

*Phaseout period*"  Coal plants designated for phaseout between January 1, 2018 through to the end of year 2029 are evaluated.


Since the ECD database does not contain the MW capacity for some of the lignite plants, MW capacity was predicted for those plants missing data using the $CO_2$ emission levels which were produced when the retired plants were in operation. 


As plant closure dates may change, the data published in the ECD database will need to be reevaluated periodically as more coal plants are selected for closure or if closure dates are extended.  

The file *Selected_EU_coal_plants.Rmd* contains a list of all coal plants within the ECD database which meet the selection criteria.  

