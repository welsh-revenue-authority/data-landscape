# Welsh land and property data landscape

This repository contains a list of the datasets about land a property that the spine might need to take account of where possible it includes sample data (where such data is available in the open).

## Unique identifiers

### Title Number

The unique identifier for each property on HM Land Registry’s property register. Used to index the `Title` and `Title Plan` documents for land registered in England and Wales. 13% of land in England and Wales in unregistered  and so will not have a `Title Number`. [^1] [^2] [^3]

* Licensing: Copyright HM Land Registry
* Custodian: [HM Land Registry][3]
* Example: `CYM23456`

###  Index Polygon ID 
The unique identifier for each ‘indicative extent’ on HM Land Registry’s property register. ([https://www.owenboswarva.com/blog/post-addr2.htm][4])

### INSPIRE ID

Unique identifiers for the INSPIRE Index Polygons that define the approximate geographical extent of land registered in England and Wales. There is a licensable dataset/service to lookup the `Title Numbers` for each `INSPIRE ID`.[^4] [^5]

* Custodian: [HM Land Registry][7]
* Licence: [Open Government Licence][8]
* Example: `15530929`

### Unique Property Reference Number (UPRN)

UPRNs are the unique identifiers for every addressable location in Great Britain.[^6] UPRNs are hierarchical which means there are parent UPRNs to group child UPRNs, for example, flats within a block of flats.[^7]

The dataset was made available under the Open Government licence in July 2020. [^8] [^9]

* Custodian: [GeoPlace][11]
* [Documentation][12]
* Example: [`10094099741`][13]
* [Wikidata][14]
* Licence: [Open Government Licence][15]

### Unique Address Reference Number (UARN)

A Unique Address Reference Number (UARN) is a unique identifier assigned to each Council Tax and Non Domestic Rate record from Valuation Office Agency.

All UARNs are mapped to UPRNs. For a minority of records, GeoPlace are unable to uniquely map UARNs to the lowest level (child) UPRN. In that case a group of UARNs are assigned to a higher level (parent) UPRN. VOA monitors which UPRNs are assigned to UARNs and there is an ongoing effort to reduce the number of UARNs that cannot be assigned to a child UPRN.[^10]

* Custodian: [Valuation Office Agency][16]
* Example: 
* Licence: 

### Unique Street Reference Number (USRN)

The Unique Street Reference Number (USRN) is an 8 digit unique identifier for every street across Great Britain. 

The Unique Street Reference Number (USRN) is an eight-digit unique identifier (a geocode) for every street across Great Britain.  The USRNs for England and Wales exists within the National Street Gazetteer (NSG), the authoritative source of information about streets in England and Wales and is a compilation of data from 173 highway authorities' Local Street Gazetteers. [^11] [^12]
* Custodian: [GeoPlace][19]
* Example: [`46406746`]()
* Licence: [Open Government Licence][21]
* * [Wikidata][22]

### Postcodes

A postcode designates an area with several addresses or a single major delivery point (sometimes non-geographic).

* Custodian: Royal Mail/Ordnance Survey/Ofcom
* Licence for postcode (+ XY coordinates) in Great Britain: [Open Government Licence][23]
* [Documentation][24]
* Example: CF37 5YR

### UDPRN
[^13]
### UMRRN
[^14]

### Flood Re Unique Identifier (FRid)
[^15]

### Meter Point Administration Number (MPAN)
[^16] [^17]

### Meter Point Reference Number (MPRN)
[^18]

### Local Authority Identification (LAID)

A unique 4 digit identifier assigned by UK government to each local authority.  Used for information exchange between central and local government.

## Geographies

### INSPIRE Index Polygons

INSPIRE Index Polygons is an open source dataset, developed to comply with the EU INSPIRE Directive (that was [maintained after EU exit][31]). It contains the locations of freehold registered property in England and Wales. It is a sub-set of the Land Registry's Index Polygons database for all freehold land and property.

* Custodian: [HM Land Registry][32]
* Licence: [Open Government Licence][33]
* [Documentation][34]
* [Example polygon (GeoJSON converted from GML)][35]
* Unique identifier: INSPIRE ID
* [Wikidata][36]

### Postcode polygons

### Postcode points (x/y)

The centroid of the postcode polygon

## Documents

### Land Registry Title

A description of the registered title. Some of the information contained is available as a [dataset extracted from the title][37].

* Licensing: Copyright HM Land Registry
* Custodian: HM Land Registry
* [Example][38]
* [Documentation][39]

### Land Registry Title Plan

* [Example][40] ([source][41]
* [Documentation][42]


### The TOpographic IDentifier or TOID
[^19][^20]

### Primary Addressable Object Name (PAON)

Defined in [BS7666:2006][44]

### Secondary Addressable Object Name (SAON)

Defined in [BS7666:2006][45]

### USRN (Unique Street Reference Number)

A unique identifier assigned to each Street.

## Data about land and property

### Land Registry price paid

Price Paid Data tracks property sales in England and Wales submitted to HM Land Registry for registration. Price Paid Data is based on the raw data released each month.

* [Documentation][46]

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

### Billing authority coordinates

Billing authority code – a unique identifier for (council tax) billing authorities.

### Cadw Listed Buildings
* Custodian: [Cadw][47]
* Unique identifier: Record Number
* Example ID: 1
* Projection system: [EPSG:27700][48] (OSGB 36)

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
* [food hygiene ratings data][49]
* [Price Paid Data][50]

[^1]:	https://www.gov.uk/government/organisations/land-registry/about

[^2]:	[https://anna.ps/blog/how-to-use-land-registry-data-to-explore-land-ownership-near-you][1]

[^3]:	[https://www.owenboswarva.com/blog/post-addr2.htm][2]

[^4]:	[https://www.owenboswarva.com/blog/post-addr2.htm][5]

[^5]:	[https://use-land-property-data.service.gov.uk/datasets/inspire][6]

[^6]:	https://www.geoplace.co.uk/addresses-streets/location-data/the-uprn

[^7]:	https://cy.ons.gov.uk/peoplepopulationandcommunity/housing/methodologies/valuationofficeagencypropertyattributedataqualityassuranceofadministrativedatausedincensus2021#practice-area-3-quality-assurance-principles-standards-and-checks-applied-to-data-supplies

[^8]:	[https://dluhcdigital.blog.gov.uk/2020/04/02/unique-property-identifiers-to-be-opened-under-open-government-license/][9]

[^9]:	[https://www.geoplace.co.uk/power-of-place/becoming-open-and-royalty-free][10]

[^10]:	https://cy.ons.gov.uk/peoplepopulationandcommunity/housing/methodologies/valuationofficeagencypropertyattributedataqualityassuranceofadministrativedatausedincensus2021#practice-area-3-quality-assurance-principles-standards-and-checks-applied-to-data-supplies

[^11]:	[https://en.wikipedia.org/wiki/Unique\_Street\_Reference\_Number][17]

[^12]:	[https://www.geoplace.co.uk/addresses-streets/location-data/usrn][18]

[^13]:	[https://www.owenboswarva.com/blog/post-addr2.htm][25]

[^14]:	[https://www.owenboswarva.com/blog/post-addr2.htm][26]

[^15]:	[https://www.owenboswarva.com/blog/post-addr2.htm][27]

[^16]:	[https://www.owenboswarva.com/blog/post-addr2.htm][28]

[^17]:	[https://en.wikipedia.org/wiki/Meter\_Point\_Administration\_Number][29]

[^18]:	[https://www.owenboswarva.com/blog/post-addr2.htm][30]

[^19]:	A TOID (Topographic Identifier) is a unique and persistent identifier for each and every feature found in OS MasterMap products.

[^20]:	[https://www.owenboswarva.com/blog/post-addr2.htm][43]

[1]:	https://anna.ps/blog/how-to-use-land-registry-data-to-explore-land-ownership-near-you
[2]:	https://www.owenboswarva.com/blog/post-addr2.htm
[3]:	https://www.gov.uk/government/organisations/land-registry
[4]:	https://www.owenboswarva.com/blog/post-addr2.htm
[5]:	https://www.owenboswarva.com/blog/post-addr2.htm
[6]:	https://use-land-property-data.service.gov.uk/datasets/inspire
[7]:	https://www.gov.uk/government/organisations/land-registry
[8]:	https://use-land-property-data.service.gov.uk/datasets/inspire/download
[9]:	https://dluhcdigital.blog.gov.uk/2020/04/02/unique-property-identifiers-to-be-opened-under-open-government-license/
[10]:	https://www.geoplace.co.uk/power-of-place/becoming-open-and-royalty-free
[11]:	https://www.geoplace.co.uk
[12]:	https://www.geoplace.co.uk/addresses-streets/location-data/the-uprn
[13]:	https://uprn.uk/10094099741#.Yfp2Yy-l2Cc
[14]:	https://www.wikidata.org/wiki/Wikidata:Property_proposal/Unique_Property_Reference_Number
[15]:	https://use-land-property-data.service.gov.uk/datasets/inspire/download
[16]:	https://www.gov.uk/government/organisations/valuation-office-agency
[17]:	https://en.wikipedia.org/wiki/Unique_Street_Reference_Number
[18]:	https://www.geoplace.co.uk/addresses-streets/location-data/usrn
[19]:	https://www.geoplace.co.uk
[21]:	https://use-land-property-data.service.gov.uk/datasets/inspire/download
[22]:	https://www.wikidata.org/wiki/Property:P8447
[23]:	https://use-land-property-data.service.gov.uk/datasets/inspire/download
[24]:	https://www.ordnancesurvey.co.uk/business-government/products/code-point-open
[25]:	https://www.owenboswarva.com/blog/post-addr2.htm
[26]:	https://www.owenboswarva.com/blog/post-addr2.htm
[27]:	https://www.owenboswarva.com/blog/post-addr2.htm
[28]:	https://www.owenboswarva.com/blog/post-addr2.htm
[29]:	https://en.wikipedia.org/wiki/Meter_Point_Administration_Number
[30]:	https://www.owenboswarva.com/blog/post-addr2.htm
[31]:	https://www.gov.uk/eu-withdrawal-act-2018-statutory-instruments/the-inspire-amendment-eu-exit-regulations-2018
[32]:	https://www.gov.uk/government/organisations/land-registry
[33]:	https://use-land-property-data.service.gov.uk/datasets/inspire/download
[34]:	https://use-land-property-data.service.gov.uk/datasets/inspire/download
[35]:	examples/inspire-example.geojson
[36]:	https://www.wikidata.org/wiki/Wikidata:Property_proposal/INSPIRE_ID
[37]:	https://use-land-property-data.service.gov.uk/datasets/nps/tech-spec/3
[38]:	examples/illustrative-title-register.png
[39]:	https://www.gov.uk/government/publications/how-to-read-a-title-register-and-title-plan/how-to-read-a-title-register
[40]:	examples/example_title_plan.pdf
[41]:	https://eservices.landregistry.gov.uk/eservices/FindAProperty/view/resources/example_title_plan.pdf
[42]:	https://www.gov.uk/government/publications/how-to-read-a-title-register-and-title-plan/how-to-read-a-title-plan
[43]:	https://www.owenboswarva.com/blog/post-addr2.htm
[44]:	https://static.geoplace.co.uk/downloads/british-standard-7776.pdf
[45]:	https://static.geoplace.co.uk/downloads/british-standard-7776.pdf
[46]:	https://www.gov.uk/guidance/about-the-price-paid-data#explanations-of-column-headers-in-the-ppd
[47]:	https://cadw.gov.wales
[48]:	https://epsg.io/27700
[49]:	http://ratings.food.gov.uk/open-data/ "food hygiene ratings data"
[50]:	https://www.gov.uk/government/collections/price-paid-data "Price Paid Data"
