# UK Department of Communities and Local Government (DCLG) data visualisation

Comparisons of data on housing held by the DCLG with data on housing from other sources, notably the nomisweb.co.uk site : NOMIS API.

## Demo

[Visualization_5](http://jsfiddle.net/nicolasterpolilli/Ran9A/4/embedded/result/)

* X axis = Permanent dwellings started, 2009/10 to 2012/13 
* Y axis = Permanent dwellings completed, circle = 1 local authority
* Radius = Numbers of households accommodated by local authorities per 1000 households 2012-Q1
## Drafts

* [Visualization_1](http://jsfiddle.net/nicolasterpolilli/x6HJq/embedded/result/)
* [Visualization_2](http://jsfiddle.net/nicolasterpolilli/J74am/embedded/result/)
* [Visualization_3](http://jsfiddle.net/nicolasterpolilli/g6cKK/embedded/result/)
* [Visualization_4](http://jsfiddle.net/nicolasterpolilli/j4ZS5/2/embedded/result/)

### First step

* SPARQL query to get data from 2 datasets via Open Data Communities API :
    * [Permanent dwellings started, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/starts/tenure)
    * [Permanent dwellings completed, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/completions/tenure)
    * [Households in temporary accommodation per 1000 households, 2011 Q2 to 2013 Q4, England, District](http://opendatacommunities.org/data/homelessness/households-accommodated-per-1000/temporary-housing-types)
* d3.js for visualization

### Doing

* NOMIS API 

### Other viz

* index.html : X axis represent england's local authorities, alphabetically ranked, Y axis represent the number of houses started / completed (2 values, 1 per dataset)
* index2.html : X axis is 10 times the absolute value of the difference between values from both datasets
* index3.html : X axis = 1st dataset, Y axis = 2nd dataset => each couple of points represent one local authority, the farest they are from the diagonal, the more different they are in both datasets, the radius is function of the value.
* index4.html : same than index3.html but with just 1 circle per local authority
