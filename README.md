# Welsh land and property data landscape

This repository contains a list of the datasets about land a property that the spine might need to take account of where possible it includes sample data (where such data is available in the open).

## Identifiers

### Land Registry Title Number

The unique identifier for each property on the property register. Used to index the ```Title``` and ```Title Plan``` documents for land registered in England and Wales. [13% of land in England and Wales in unregistered](https://www.gov.uk/government/organisations/land-registry/about) and so will not have a ```Title Number```.

* Licensing: Copyright HM Land Registry
* Custodian: [HM Land Registry](https://www.gov.uk/government/organisations/land-registry)
* Example: ```CYM23456```

### INSPIRE ID

Unique identifiers for the INSPIRE Index Polygons that define the approximate geographical extent of land registered in England and Wales. There is a licensable dataset/service to lookup the ```Title Numbers``` for each ```INSPIRE ID```.

* Custodian: [HM Land Registry](https://www.gov.uk/government/organisations/land-registry)
* Licence: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* Example: ```15530929```

### Unique Property Reference Number (UPRN)

UPRNs are the unique identifiers for every addressable location in Great Britain. UPRNs are hierarchical which means there are parent UPRNs to group child UPRNs, for example, flats within a block of flats.

* Custodian: GeoPlace (a public sector limited liability partnership between the Local Government Association and Ordnance Survey)
* [Documentaiton](https://www.geoplace.co.uk/addresses-streets/location-data/the-uprn)
* Example: [```10094099741```](https://uprn.uk/10094099741#.Yfp2Yy-l2Cc)
* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Property_proposal/Unique_Property_Reference_Number)
* Licence: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)

### Unique Address Reference Number (UARN)

A Unique Address Reference Number (UARN) is a unique identifier assigned to each Council Tax and Non Domestic Rate record from Valuation Office Agency.

All UARNs are mapped to UPRNs. For a minority of records, GeoPlace are unable to uniquely map UARNs to the lowest level (child) UPRN. In that case a group of UARNs are assigned to a higher level (parent) UPRN. VOA monitors which UPRNs are assigned to UARNs and there is an ongoing effort to reduce the number of UARNs that cannot be assigned to a child UPRN. ([source](https://www.ons.gov.uk/peoplepopulationandcommunity/housing/methodologies/valuationofficeagencypropertyattributedataqualityassuranceofadministrativedatausedincensus2021#practice-area-1-operational-context-and-administrative-data-collection))
 
* Custodian: [Valuation Office Agency](https://www.gov.uk/government/organisations/valuation-office-agency)
* Example:
* Licence:

### Postcodes

A postcode designates an area with several addresses or a single major delivery point (sometimes non-geographic).

* Custodian: Royal Mail/Ordnance Survey/Ofcom
* Licence for postcode (+ XY coordinates) in Great Britain: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* [Documentaiton](https://www.ordnancesurvey.co.uk/business-government/products/code-point-open)
* Example: CF37 5YR

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

## Documents

### Land Registry Title

A description of the registered title. Some of the information contained is available as a [dataset extracted from the title](https://use-land-property-data.service.gov.uk/datasets/nps/tech-spec/3).

* Licensing: Copyright HM Land Registry
* Custodian: HM Land Registry
* [Example](examples/illustrative-title-register.png)
* [Documentation](https://www.gov.uk/government/publications/how-to-read-a-title-register-and-title-plan/how-to-read-a-title-register)

### Land Registry Title Plan

* [Example](examples/example_title_plan.pdf) ([source](https://eservices.landregistry.gov.uk/eservices/FindAProperty/view/resources/example_title_plan.pdf)
* [Documentation](https://www.gov.uk/government/publications/how-to-read-a-title-register-and-title-plan/how-to-read-a-title-plan)


### The TOpographic IDentifier or TOID

### Primary Addressable Object Name (PAON)

Defined in [BS7666:2006](https://static.geoplace.co.uk/downloads/british-standard-7776.pdf)

### Secondary Addressable Object Name (SAON)

Defined in [BS7666:2006](https://static.geoplace.co.uk/downloads/british-standard-7776.pdf)

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

### Transaction unique identifier

Custodian: Land Registry

## Other

### Special Category Code (SCat Code)
* Custodian: VAO

### Primary Description Code
* Custodian: VAO

### VOA Rating lists

* https://voaratinglists.blob.core.windows.net/html/documents/2017%20Compiled%20List%20and%20SMV%20Data%20Specification.pdf

### Cadw Listed Buildings
* Custodian: [Cadw](https://cadw.gov.wales)
* Unique identifier: Record Number
* Example ID: 1
* Projection system: [EPSG:27700](https://epsg.io/27700) (OSGB 36)

https://datamap.gov.wales/layers/inspire-wg:Cadw_ListedBuildings


## Sources and links

* https://www.owenboswarva.com/blog/post-addr2.htm
* https://www.owenboswarva.com/blog/post-addr1.htm
* https://www.geoplace.co.uk/blog/2018/persistent-and-well-behaved-identifiers
* https://www.geoplace.co.uk/addresses-streets/data-in-use/glossary
* https://cadw.gov.wales/advice-support/cof-cymru/downloads
* https://anna.ps/blog/how-to-use-land-registry-data-to-explore-land-ownership-near-you
* https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/923483/geospatial-data-catalogue-hm-land-registry.csv/preview
* https://cy.ons.gov.uk/peoplepopulationandcommunity/housing/methodologies/valuationofficeagencypropertyattributedataqualityassuranceofadministrativedatausedincensus2021#practice-area-3-quality-assurance-principles-standards-and-checks-applied-to-data-supplies
* https://www.gov.uk/guidance/council-tax-manual
