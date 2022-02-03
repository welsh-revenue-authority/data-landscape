# Welsh land and property data landscape

This repository contains a list of the datasets about land a property that the spine might need to take account of where possible it includes sample data (where such data is available in the open).

* [Unique identifiers for property and land](identifiers.md)
* [Documents](documents.md)
* [Geospatial data](geospatial.md)
* [Temporal data](temporal.md)
* [Other data](other.md)

## Geographies

### INSPIRE Index Polygons

INSPIRE Index Polygons is an open source dataset, developed to comply with the EU INSPIRE Directive (that was [maintained after EU exit](https://www.gov.uk/eu-withdrawal-act-2018-statutory-instruments/the-inspire-amendment-eu-exit-regulations-2018)). It contains the locations of freehold registered property in England and Wales. It is a sub-set of the Land Registry's Index Polygons database for all freehold land and property.

* Custodian: [HM Land Registry](https://www.gov.uk/government/organisations/land-registry)
* Licence: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* [Documentation](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* [Example polygon (GeoJSON converted from GML)](examples/inspire-example.geojson)
* Unique identifier: INSPIRE ID
* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Property_proposal/INSPIRE_ID)

### Postcode polygons

### Postcode points (x/y)

The centroid of the postcode polygon


### The TOpographic IDentifier or TOID
[^1][^2]

### Primary Addressable Object Name (PAON)

Defined in [BS7666:2006](https://static.geoplace.co.uk/downloads/british-standard-7776.pdf)

### Secondary Addressable Object Name (SAON)

Defined in [BS7666:2006](https://static.geoplace.co.uk/downloads/british-standard-7776.pdf)

### USRN (Unique Street Reference Number)

A unique identifier assigned to each Street.

## Data about land and property

### Land Registry price paid

Price Paid Data tracks property sales in England and Wales submitted to HM Land Registry for registration. Price Paid Data is based on the raw data released each month.

* [Documentation](https://www.gov.uk/guidance/about-the-price-paid-data#explanations-of-column-headers-in-the-ppd)

## Unique identifiers for transactions

### Transaction unique identifier

Custodian: Land Registry

## Other

### Special Category Code (SCat Code)
* Custodian: VAO

### Primary Description Code
* Custodian: VAO

### VOA Rating lists

* https://voaratinglists.blob.core.windows.net/html/documents/2017%20Compiled%20List%20and%20SMV%20Data%20Specification.pdf

### Billing authority coordinates

Billing authority code – a unique identifier for (council tax) billing authorities.


https://datamap.gov.wales/layers/inspire-wg:Cadw\_ListedBuildings


## Sources and links

* https://www.owenboswarva.com/blog/post-addr2.htm
* https://www.owenboswarva.com/blog/post-addr1.htm
* https://www.geoplace.co.uk/blog/2018/persistent-and-well-behaved-identifiers
* https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment\_data/file/923483/geospatial-data-catalogue-hm-land-registry.csv/preview
* https://cy.ons.gov.uk/peoplepopulationandcommunity/housing/methodologies/valuationofficeagencypropertyattributedataqualityassuranceofadministrativedatausedincensus2021#practice-area-3-quality-assurance-principles-standards-and-checks-applied-to-data-supplies

## To review
* https://www.gov.uk/guidance/council-tax-manual
* https://www.geoplace.co.uk/addresses-streets/data-in-use/glossary
* https://cadw.gov.wales/advice-support/cof-cymru/downloads
* [food hygiene ratings data](http://ratings.food.gov.uk/open-data/ "food hygiene ratings data")
* [Price Paid Data](https://www.gov.uk/government/collections/price-paid-data "Price Paid Data")

[^1]:	A TOID (Topographic Identifier) is a unique and persistent identifier for each and every feature found in OS MasterMap products.

[^2]:	[https://www.owenboswarva.com/blog/post-addr2.htm][43]
