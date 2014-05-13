# UK Department of Communities and Local Government (DCLG) data visualisation

Comparisons of data on housing held by the DCLG with data on housing from other sources, notably the nomisweb.co.uk site : NOMIS API.

### First step

* I did not use SPARQL queries (need help I guess :) )
* I've taken 2 csv files about the same topic : 
    * [Permanent dwellings started, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/starts/tenure)
    * [Permanent dwellings completed, 2009/10 to 2012/13, England, District By Tenure
](http://opendatacommunities.org/data/house-building/completions/tenure)
* I've prepared the .csv datasets (id column etc)
* The idea is to compare two datasets from two sources so I've made a scatter plot where, on the diagonal, there are the values that are the same in both datasets. Then, the more different the values from both datasets, the farest from the diagonal. There is a color code (the more different, the more 'red'). I've put a variable 'limit' so you can fix the 'red limit'.
* Circles radius are proportionate to the values.
* If you hover the mouse over the point, it showes the name of the local authority and the value.
* If you load the same dataset, it showes the diagonal.

### Issues

* It looks like a large part of the dataset is not showed 
* Everything can be improved ! :)
* I've to change the names because I've made it specifically for those datasets.
* There is no problem when the datasets have the same number of datum
* SPARQL
