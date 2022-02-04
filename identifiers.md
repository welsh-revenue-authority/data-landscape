# Unique identifiers for property and land

## Title Number

The unique identifier for each property on HM Land Registry’s property register. Used to index the `Title` and `Title Plan` documents for land registered in England and Wales. 13% of land in England and Wales in unregistered  and so will not have a `Title Number`. [^1] 

* Licensing: Copyright HM Land Registry
* Custodian: [HM Land Registry](https://www.gov.uk/government/organisations/land-registry)
* Example: `CYM23456`

## Polygon ID
The unique identifier for each ‘indicative extent’ on HM Land Registry’s property register. The relationship between the registered title and `Polygon ID` is managed through the title number. 

* Licensing: Copyright HM Land Registry
* Custodian: [HM Land Registry](https://www.gov.uk/government/organisations/land-registry)
* Example: 
* [Documentation](https://use-land-property-data.service.gov.uk/datasets/nps)

## INSPIRE ID
Unique identifiers for the INSPIRE Index Polygons that define the approximate geographical extent of land registered in England and Wales. There is a licensable dataset/service to lookup the `Title Numbers` for each `INSPIRE ID`. 

* Custodian: [HM Land Registry](https://www.gov.uk/government/organisations/land-registry)
* Licence: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download)
* Example: `15530929`
* [Documentation](https://use-land-property-data.service.gov.uk/datasets/inspire)

## Unique Property Reference Number (UPRN)

UPRNs are the unique identifiers for every addressable location in Great Britain.[^2] UPRNs are hierarchical which means there are parent UPRNs to group child UPRNs, for example, flats within a block of flats.[^3]

The dataset was made available under the Open Government licence in July 2020. [^4] [^5]

* Custodian: [GeoPlace](https://www.geoplace.co.uk)
* [Documentation](https://www.geoplace.co.uk/addresses-streets/location-data/the-uprn)
* Example: [`10094099741`](https://uprn.uk/10094099741#.Yfp2Yy-l2Cc)
* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Property_proposal/Unique_Property_Reference_Number)
* Licence: [Open Government Licence](https://www.ordnancesurvey.co.uk/business-government/tools-support/open-mastermap-programme/open-id-policy)

## Unique Address Reference Number (UARN)

A Unique Address Reference Number (UARN) is a unique identifier assigned to each Council Tax and Non Domestic Rate record from Valuation Office Agency.

All UARNs are mapped to UPRNs. For a minority of records, GeoPlace are unable to uniquely map UARNs to the lowest level (child) UPRN. In that case a group of UARNs are assigned to a higher level (parent) UPRN. VOA monitors which UPRNs are assigned to UARNs and there is an ongoing effort to reduce the number of UARNs that cannot be assigned to a child UPRN.[^6] 

* Custodian: [Valuation Office Agency](https://www.gov.uk/government/organisations/valuation-office-agency)
* Example:
* Licence:

## Unique Street Reference Number (USRN)

The Unique Street Reference Number (USRN) is an 8 digit unique identifier for every street across Great Britain.

The Unique Street Reference Number (USRN) is an eight-digit unique identifier (a geocode) for every street across Great Britain.  The USRNs for England and Wales exists within the National Street Gazetteer (NSG), the authoritative source of information about streets in England and Wales and is a compilation of data from 173 highway authorities' Local Street Gazetteers.  [^7] The dataset was made available under the Open Government licence in July 2020. [^8] [^9]

* Custodian: [GeoPlace](https://www.geoplace.co.uk)
* Example: [`46406746`]()
* Licence: [Open Government Licence](https://www.ordnancesurvey.co.uk/business-government/tools-support/open-mastermap-programme/open-id-policy)
* [Wikidata](https://www.wikidata.org/wiki/Property:P8447)
* [Wikipedia](https://en.wikipedia.org/wiki/Unique%5C_Street%5C_Reference%5C_Number)

## Postcode

A postcode designates an area with several addresses or a single major delivery point (sometimes non-geographic).

* Custodian: Royal Mail/Ordnance Survey/Ofcom
* Licence: [Open Government Licence](https://use-land-property-data.service.gov.uk/datasets/inspire/download) (for postcode + XY coordinates in Great Britain)
* [Documentation](https://www.ordnancesurvey.co.uk/business-government/products/code-point-open)
* Example: CF37 5YR
* [Wikipedia](https://en.wikipedia.org/wiki/Postcodes_in_the_United_Kingdom)

## Unique Delivery Point Reference Number (UDPRN)

The `UDPRN` is a unique identifier for deliverable addresses and is number issued by Royal Mail. It is 8 digits long. [^10] [^11]

* Custodian: Royal Mail
* Licence: Copyright Royal Mail
* [Documentation](https://www.poweredbypaf.com/wp-content/uploads/2017/07/Latest-Programmers_guide_Edition-7-Version-6.pdf)
* Example:

## Unique Multiple Residence Reference Number (UMRRN)

The `UDPRN` is a unique identifier for addresses with shared delivery points (e.g. flats with a shared letter box). It does not include bedsits, marinas, caravan sites, hostels, hotels or prisons.[^12][^13]

* Custodian: Royal Mail
* Licence: Copyright Royal Mail
* [Documentation](https://www.poweredbypaf.com/wp-content/uploads/2017/07/Latest-Programmers_guide_Edition-7-Version-6.pdf)
* Example:

## Flood Re Unique Identifier (FRid)
Flood Re is a joint initiative between UK Government and insurers. There is a Flood Re unique identifier (FRid) for all of the 30 million UK residential
properties. It is represented by 32 lowercase hexadecimal digits, displayed
in five groups separated by hyphens, in the form 8-4-4-4-12
for a total of 36 characters (32 alphanumeric characters and
four hyphens). [^14]

## Meter Point Administration Number (MPAN)

A Meter Point Administration Number, also known as MPAN, Supply Number or S-Number, is a 21-digit reference used in Great Britain to uniquely identify electricity supply points such as individual domestic residences. 

* Custodian:
* Licence:
* Documentation:
* Example:
* [Wikipedia]([https://en.wikipedia.org/wiki/Meter%5C_Point%5C_Administration%5C_Number])


## Meter Point Reference Number (MPRN)

A Meter Point Reference Number (`MPRN`) is a unique number assigned to every single gas supply point in the UK and is used to identify individual gas supply points. They are made up of numbers only and don’t contain any letters. The format of an `MPRN` is quite standard and consists of between 6 and 11 digits. [^15]

* Custodian:
* Licence:
* Documentation:
* Example:

## Local Authority Business ID (Local Authorities / Food Standards Agency)
Local authorities maintain their own `business premises IDs`. The Food Standards Agency uses these food hygiene rating data includes references. 

* Custodian:
* Licence:
* Documentation:
* Example:
* [ Local Authority Business ID on data.gov.uk](https://data.gov.uk/dataset/bee79b5d-0bc4-430f-88ed-cedd3c0aac7e/uk-food-hygiene-rating-data-wales-welsh-language-food-standards-agency)

## Cadw Listed Buildings Record Number
Listed buildings in Wales are assigned a `Record Number` by Cadw.
* Custodian: [Cadw](https://cadw.gov.wales)
* Unique identifier: `Record Number`
* Example ID: 1

## The Topographic Identifier  (TOID)
A `TOID` (Topographic Identifier) is a unique and persistent identifier for each and every feature found in OS MasterMap products. [^16]

* Licence: [Open Government Licence](https://www.ordnancesurvey.co.uk/business-government/tools-support/open-mastermap-programme/open-id-policy)
* [Wikidata](https://www.wikidata.org/wiki/Property:P3120)
* [ OS Open TOID  on data.gov.uk](https://data.gov.uk/dataset/7f8b7752-a49f-464e-84ae-b2551f62b926/os-open-toid)

## Address (BS7666:2006)

Local authorities maintain Local Land & Property Gazetteers to a standard format. Geoplace collect these together as the National Land & Property Gazetteer for England and Wales.

* Custodian: Local Authorities / Geoplace
* Unique identifier: Address
* Example ID:

[^1]:	https://www.gov.uk/government/organisations/land-registry/about

[^2]:	https://www.geoplace.co.uk/addresses-streets/location-data/the-uprn

[^3]:	https://cy.ons.gov.uk/peoplepopulationandcommunity/housing/methodologies/valuationofficeagencypropertyattributedataqualityassuranceofadministrativedatausedincensus2021#practice-area-3-quality-assurance-principles-standards-and-checks-applied-to-data-supplies

[^4]:	[https://dluhcdigital.blog.gov.uk/2020/04/02/unique-property-identifiers-to-be-opened-under-open-government-license/](https://dluhcdigital.blog.gov.uk/2020/04/02/unique-property-identifiers-to-be-opened-under-open-government-license/)

[^5]:	[https://www.geoplace.co.uk/power-of-place/becoming-open-and-royalty-free](https://www.geoplace.co.uk/power-of-place/becoming-open-and-royalty-free)

[^6]:	https://cy.ons.gov.uk/peoplepopulationandcommunity/housing/methodologies/valuationofficeagencypropertyattributedataqualityassuranceofadministrativedatausedincensus2021#practice-area-3-quality-assurance-principles-standards-and-checks-applied-to-data-supplies

[^7]:	[https://www.geoplace.co.uk/addresses-streets/location-data/usrn](https://www.geoplace.co.uk/addresses-streets/location-data/usrn)

[^8]:	[https://dluhcdigital.blog.gov.uk/2020/04/02/unique-property-identifiers-to-be-opened-under-open-government-license/](https://dluhcdigital.blog.gov.uk/2020/04/02/unique-property-identifiers-to-be-opened-under-open-government-license/)

[^9]:	[https://www.geoplace.co.uk/power-of-place/becoming-open-and-royalty-free](https://www.geoplace.co.uk/power-of-place/becoming-open-and-royalty-free)

[^10]:	[https://www.experian.co.uk/business/glossary/udprn/](https://www.experian.co.uk/business/glossary/udprn/)

[^11]:	[https://www.poweredbypaf.com/wp-content/uploads/2017/07/Latest-Programmers\_guide\_Edition-7-Version-6.pdf](https://www.poweredbypaf.com/wp-content/uploads/2017/07/Latest-Programmers_guide_Edition-7-Version-6.pdf)

[^12]:	[https://docs.experianaperture.io/address-validation/global-datasets/asset/adg\_mrf.pdf](https://docs.experianaperture.io/address-validation/global-datasets/asset/adg_mrf.pdf)

[^13]:	[https://www.poweredbypaf.com/wp-content/uploads/2017/07/Latest-Programmers\_guide\_Edition-7-Version-6.pdf](https://www.poweredbypaf.com/wp-content/uploads/2017/07/Latest-Programmers_guide_Edition-7-Version-6.pdf)

[^14]:	[https://www.floodre.co.uk/wp-content/uploads/Bordereaux-Completion-Guide-V4.0.pdf](https://www.floodre.co.uk/wp-content/uploads/Bordereaux-Completion-Guide-V4.0.pdf)

[^15]:	[https://www.gasconnections.co.uk/meter-point-reference-number/](https://www.gasconnections.co.uk/meter-point-reference-number/)

[^16]:	[https://www.owenboswarva.com/blog/post-addr2.htm][43]