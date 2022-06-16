# Challenges loading data

### Sources containing different feature types

We tried to add the [National Parks data](https://datamap.gov.wales/layers/inspire-nrw:NRW_NATIONAL_PARK) from DataMapWales.

We tried to load both the Geojson and the GML formats. Both resulted in this error
```
Error 6
Feature write errors:
Creation error for features from #-9223372036854775808 to #-9223372036854775808. Provider errors was: 
PostGIS error while adding features: ERROR:  Geometry type (MultiPolygon) does not match column type (Polygon)

Only 0 of 3 features written.
```

Looking at the data, 2 of the features are
```
"type": "Polygon"
```

And 1 feature is
```
"type": "MultiPolygon"
```

This might be the cause of the issue.

To investigate.
