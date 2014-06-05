# UK Housing Market data visualisation

Comparisons of data on housing held by the [DCLG](http://opendatacommunities.org) with data on housing from the [NOMIS API](http://www.nomisweb.co.uk).

## Demo

[Demo](http://jsfiddle.net/nicolasterpolilli/up4vW/11/embedded/result/)

* Circles = Local authorities (authorities that form the lower tier or only tier of local government: so district councils, unitary authorities, metropolitan districts and London boroughs - but not county councils)
* Radius = Numbers of dwellings, 2012
* Color = Function of employment rate - aged 16-64, 2013, logarithmic scale
* Tooltip onclick with links to ressources URI

## Informations

* SPARQL query to get data from datasets via Open Data Communities API :
    * [Number of dwellings by tenure and district](http://opendatacommunities.org/data/housing-market/dwelling-stock/tenure)
    * [Permanent dwellings started, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/starts/tenure)
    * [Permanent dwellings completed, 2009/10 to 2012/13, England, District By Tenure](http://opendatacommunities.org/data/house-building/completions/tenure)
    * [Households in temporary accommodation per 1000 households, 2011 Q2 to 2013 Q4, England, District](http://opendatacommunities.org/data/homelessness/households-accommodated-per-1000/temporary-housing-types)
    * [Ratio of median house price to median earnings by district, from 1997](http://opendatacommunities.org/data/housing-market/ratio/house-prices-ratio/med-house-price-to-earnings)
* NOMIS API :
    * Employment rate - aged 16-64, 2013, England, District
    * [Help to use NOMIS API](https://github.com/the-frey/odc_nomis)
* d3.js for visualization
* [ColorBrewer2](http://colorbrewer2.org)

## Tutorial

* [Tutorial](https://github.com/NTerpo/DCLG_data_visualization/blob/master/tutorial.md)
* [Tutorial code](https://github.com/NTerpo/DCLG_data_visualization/blob/master/tutorial.html)
* [Tutorial result](http://jsfiddle.net/nicolasterpolilli/7ed26/5/embedded/result/)