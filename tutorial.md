# How to use d3.js to visualize Open Data Communities and NOMIS data

I've started an internship at [Swirrl](http://www.swirrl.com) a few weeks ago, and as the Swirrl motto "The Linked Data Company" let presume I had to dig into linked data.
I had some knowledge in web developpement but I was almost a newbie, you just need to know a little bit of HTML / CSS / Javascript. This tutorial aims to learn you to :

* Query linked data using SPARQL
* Query an API
* Visualize data on a scatter plot using [d3.js](http://d3js.org)

[You can access the code on GitHub](https://github.com/NTerpo/DCLG_data_visualization) and [here is the demo](http://jsfiddle.net/nicolasterpolilli/7ed26/5/embedded/result/)

## Step one, find linked data

To start we are going to get some data ! This is probably the most difficult part of the tutorial. Indeed nobody is naturally used to [semantic web standard's RDF](http://en.wikipedia.org/wiki/Resource_Description_Framework) ! You probably
know how to use an Excel spreadsheet, a CSV file or a SQL database, but RDF is, let say different... To understand why data are "linked", try to imagine what the internet looked like before the "link" was invented :
a "poor" list of ressources. Links between ressources have given the internet a lot of opportunities ! The idea with linked data is exactly the same, you have a huge amount of data with links between them...
Still difficult to imagine ? Don't worry we will try it on an example but you do have to imagine how powerful what you are doing can be !

### What are we doing and where those "linked data" are ?

There are more and more linked data available but we will focus on Open Data Communities which is the UK Department for Communities and Local Government's official Linked Open Data site.
Data are organized by theme and we are first going to work on [House building data](http://opendatacommunities.org/themes/house-building).

==> screenshot 1

The scatter plot we are going to make will compare the number of houses started and the number of houses completed, in one year, for each local authority in England.
The X axis will be house started and the Y axis will be house completed. Later on the tutorial we will add labour market data and homelessness data so the scatter plot 
can help you understand the housing policy of each local authority.

## Step two, basic scatter plot with d3.js

### 

## Step three, improve your visualization 

### Color

### Circles size

## Step four, compare between two time periods