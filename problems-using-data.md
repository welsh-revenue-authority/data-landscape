# Problems using published data 

We are documenting issues we've faced when using data.

### Inconsistencies between datasets about the same type of thing

There are 2 different versions of [local authority boundaries](https://datamap.gov.wales/layergroups/inspire-wg:LocalAuthorities). There is a dataset for the high water mark boundaries and a dataset for the low water mark boundaries.

There are inconsistencies between the attributes used by the datasets which could make it more difficult for service builders to use it.

For example, low water mark is
```
code: "W06000021"
name_cy: "Sir Fynwy"
name: "Monmouthshire"
ogc_fid: 21
```

And high water marks is,
```
code: "W06000021"
name_cy: "Sir Fynwy"
name_en: "Monmouthshire"
ogc_fid: 21
```

This could cause a problem if a service was built based on the `name` attribute and the service also wanted to use the high water mark data.
