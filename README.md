# open-data-research
Docs, notes, and miscellany in exploring the possibility for making GSCPC data free and open

## What does 'open data' mean?

Tim Berners-Lee, inventor of the World Wide Web, outlines a 5-star ranking system that offers some insight:

> ★	Available on the web (whatever format) but with an open licence, to be Open Data
> 
★★	Available as machine-readable structured data (e.g. excel instead of image scan of a table)
>
★★★	as (2) plus non-proprietary format (e.g. CSV instead of excel)
>
★★★★	All the above plus, Use open standards from W3C (RDF and SPARQL) to identify things, so that people can point at your stuff
>
★★★★★	All the above, plus: Link your data to other people’s data to provide context

[(Source)](http://www.w3.org/DesignIssues/LinkedData.html)

Perhaps important to note here that PDF != open data. It may be used to present an interpretation or rendering of data, but doesn't necessarily allow access to the underlying data in a [machine readable format](https://www.data.gov/developers/blog/primer-machine-readability-online-documents-and-data).

## Our reliance on open data

- Census/ACS data
- Imagery from USGS, KY Above
- Soil data
- Traffic/Crash data

## Real-life examples where open data could have helped

- A realtor wanted to use the [NRCS soil survey tool](http://websoilsurvey.sc.egov.usda.gov/App/WebSoilSurvey.aspx). That tool is pretty cool because it lets you upload a shapefile of an area of interest and then returns a nifty map and report based on whatever data they have and you filter for that area. If we did a little training on how to use QGIS and had our data openly available, she could likely have done this herself.