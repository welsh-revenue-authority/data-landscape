# Data landscape

This repository contains a list of the data sets about land a property that the spine might need to take account of where possible it includes sample data (where such data is available in the open).

## Land and property identifiers

### Land Registry Title Number

The unique identifier for each property on the property register.

### UPRNs

UPRNs are the unique identifiers for every addressable location in Great Britain.

* Custodian: GeoPlace (a public sector limited liability partnership between the Local Government Association and Ordnance Survey)
* [Documentaiton](https://www.geoplace.co.uk/addresses-streets/location-data/the-uprn)
* Example:
* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Property_proposal/Unique_Property_Reference_Number)
* Licence: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)

### Unique Address Reference Number (UARN)

A Unique Address Reference Number (UARN) is a unique identifier assigned to each Council Tax and Non Domestic Rate record from Valuation Office Agency

* Custodian: VOA

### The TOpographic IDentifier or TOID

### Primary Addressable Object Name (PAON)

Defined in [BS7666:2006](https://static.geoplace.co.uk/downloads/british-standard-7776.pdf)

### Secondary Addressable Object Name (SAON)

Defined in [BS7666:2006](https://static.geoplace.co.uk/downloads/british-standard-7776.pdf)

### INSPIRE Index Polygons

INSPIRE Index Polygons is an open source dataset, developed to comply with the EU INSPIRE Directive (that was [maintained after EU exit](https://www.gov.uk/eu-withdrawal-act-2018-statutory-instruments/the-inspire-amendment-eu-exit-regulations-2018)). It contains the locations of freehold registered property in England and Wales. It is a sub-set of the Land Registry's Index Polygons database for all freehold land and property.

* Custodian: HM Land Registry
* Licence: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* [Documentation](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* [Example polygon (GeoJSON converted from GML)](examples/inspire-example.geojson)
* Unique identifier: INSPIRE ID
* Example ID: 15530929
* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Property_proposal/INSPIRE_ID)

## Addresses and Postcodes

### Postcodes

A postcode designates an area with several addresses or a single major delivery point (sometimes non-geographic).

* Custodian: Royal Mail/Ordnance Survey/Ofcom
* Licence for postcode + XY coordinates in Great Britain: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* [Documentaiton](https://www.ordnancesurvey.co.uk/business-government/products/code-point-open)
* Licence for postcode + polygon in UK:
* Example: CF99 1NA

### USRN (Unique Street Reference Number)

A unique identifier assigned to each Street.

## Administrative areas and identifiers

### LAID (Local Authority Identification)

A unique 4 digit identifier assigned by central government to each local authority.  Used for information exchange between central and local government.

## Data about land and property

### Land Registry price paid

Price Paid Data tracks property sales in England and Wales submitted to HM Land Registry for registration. Price Paid Data is based on the raw data released each month.

* [Documentation](https://www.gov.uk/guidance/about-the-price-paid-data#explanations-of-column-headers-in-the-ppd)

## Transaction identifiers

Custodian: Land Registry

### Transaction unique identifier


## Sources and links

https://www.owenboswarva.com/blog/post-addr2.htm
https://www.owenboswarva.com/blog/post-addr1.htm
https://www.geoplace.co.uk/blog/2018/persistent-and-well-behaved-identifiers
https://www.geoplace.co.uk/addresses-streets/data-in-use/glossary
