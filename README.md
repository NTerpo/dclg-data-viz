# UK Department of Communities and Local Government (DCLG) data visualisation

Comparisons of data on housing held by the DCLG with data on housing from other sources, notably the nomisweb.co.uk site : NOMIS API.

### First step

* SPARQL query to get data from 2 datasets :
    * [Permanent dwellings started, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/starts/tenure)
    * [Permanent dwellings completed, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/completions/tenure)
* d3.js for visualization
* The X axis represent england's local authorities, alphabetically ranked
* The Y axis represent the number of houses started / completed (2 values, 1 per dataset)
* To compare the two datasets there is a color code = you can fix an acceptable limit of differences between both datasets 
    * Over this limit circles are red 
    * Blue means thats both values are the same
* When you hover each circles you get the name of the local authority and both values

### Next step

* on("click") function to have different way to sort the scatter plot
* NOMIS API
 
