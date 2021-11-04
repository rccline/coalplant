**README**  
<br>
This repository examines a list of European coal plants and transmission nodes that meet certain criteria.

The data source for this project comes in part from the [*European Coal Database* (ECD)](https://beyond-coal.eu/database/) maintained by the *Europe Beyond Coal* campaign for the period 2005 to 2020.  This data is used to screen coal plants to identify coal plants with a power capacity greater than 800 MW which have been retired or that are scheduled to be retired in the near future.

*Phaseout period*"  Coal plants designated for phaseout between January 1, 2018 through to the end of year 2029 are evaluated.


Since the ECD database does not contain the $CO_2$ levels which were produced when the retired plants were in operation, a linear model derived using data fromthe ECD database are used to estimate the plant MW capacity by analyzing the CO2 production from existing plant operations at the threshold of 800 MW. 

The first document in this repository is *coal_database.Rmd* which is an analysis of the ECD data to estimate CO2 levels for lignite and hard coal plants which produce 800 MW of power. 

*Residuals.Rmd* applies linear regression models to predict power capacity predicated on $CO_2$ emissions.  The residuals of the linear regression models are analyzed to assess goodness fit of the models to determine if the models are a reasonable predictor for calcualating $CO_2$ levels to estimate power capacity to select power plants to meet the inclusion criteria.   

As plant closure dates may change, the data published in the ECD database will need to be reevaluated periodically.  