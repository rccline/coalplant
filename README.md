**README**  
<br>
This repository examines a list of European coal plants and transmission nodes that meet certain criteria.

The first RMarkdown document identifies the coal plants with a power capacity greater than 800 MW which have been retired or that are scheduled to be retired in the near future.

The data used to screen coal plants is from the [*European Coal Database* (ECD)](https://beyond-coal.eu/database/) maintained by the *Europe Beyond Coal* campaign for the period 2005 to 2019. 

Since the ECD database does not contain the $CO_2$ levels which were produced when the retired plants were in operation, a linear model derived using data from German coal plants is used to estimate the plant MW capacity by analyzing the $CO_2$ production from existing plant operations at the threshold of 800 MW.  


