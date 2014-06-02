# UK DCLG data visualisation

Comparisons of data on housing held by the DCLG with data on housing from other sources, notably the nomisweb.co.uk site : NOMIS API.

## Demo

[Demo](http://jsfiddle.net/nicolasterpolilli/up4vW/5/embedded/result/)

* X axis = Permanent dwellings started, 2011-12 / 2012-13 
* Y axis = Permanent dwellings completed, 2011-12 / 2012-13 
* Circles = Local authorities
* Radius = Numbers of households accommodated by local authorities per 1000 households 2012-Q1
* Color = Function of 2012 jobs density, logarithmic scale
* Tooltip onclick with links to ressources URI
* Logarithmic scale

## Informations

* SPARQL query to get data from datasets via Open Data Communities API :
    * [Permanent dwellings started, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/starts/tenure)
    * [Permanent dwellings completed, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/completions/tenure)
    * [Households in temporary accommodation per 1000 households, 2011 Q2 to 2013 Q4, England, District](http://opendatacommunities.org/data/homelessness/households-accommodated-per-1000/temporary-housing-types)
* NOMIS API :
    * Jobs density, 2012, England, District
    * [Help to use NOMIS API](https://github.com/the-frey/odc_nomis)
* d3.js for visualization
* [ColorBrewer2](http://colorbrewer2.org)
