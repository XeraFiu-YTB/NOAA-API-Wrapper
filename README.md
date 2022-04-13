# NOAA Library by Bastard Nathan
---
## List of Endpoints
- [datacategories](#datacategories)
- [datatypes](#datatypes)
- [datasets](#datasets)
- [locationcategories](#locationcategories)
- [stations](#stations)
- [locations](#locations)
- [data](#data)

## **__datacategories__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| [locationid](#locationid) | false |
| [stationid](#stationid) | false |
| [startdate](#date) | false |
| [enddate](#date) | false |
| [sortfield](#sortfield) | false |
| [sortorder](#sortorder) | false |
| [limit](#limit) | false |
| [offset](#offset) | false |

## **__datatypes__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| [locationid](#locationid) | false |
| [stationid](#stationid) | false |
| [datacategoryid](#datacategoryid) | false |
| [startdate](#date) | false |
| [enddate](#date) | false |
| [sortfield](#sortfield) | false |
| [sortorder](#sortorder) | false |
| [limit](#limit) | false |
| [offset](#offset) | false |

## **__datasets__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| [locationid](#locationid) | false |
| [stationid](#stationid) | false |
| [startdate](#date) | false |
| [enddate](#date) | false |
| available | false |
| legacy | false |
| [sortfield](#sortfield) | false |
| [sortorder](#sortorder) | false |
| [limit](#limit) | false |
| [offset](#offset) | false |

## **__locationcategories__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| [startdate](#date) | false |
| [enddate](#date) | false |
| [sortfield](#sortfield) | false |
| [sortorder](#sortorder) | false |
| [limit](#limit) | false |
| [offset](#offset) | false |

## **__stations__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| [locationid](#locationid) | false |
| [datacategoryid](#datacategoryid) | false |
| [datatypeid](#datatypeid) | false |
| [extent](#extent) | false |
| [startdate](#date) | false |
| [enddate](#date) | false |
| [sortfield](#sortfield) | false |
| [sortorder](#sortorder) | false |
| [limit](#limit) | false |
| [offset](#offset) | false |

## **__locations__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| [locationcategoryid](#locationcategoryid) | false |
| parentid | false |
| [startdate](#date) | false |
| [enddate](#date) | false |
| [sortfield](#sortfield) | false |
| [sortorder](#sortorder) | false |
| [limit](#limit) | false |
| [offset](#offset) | false |

## **__data__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| [datatypeid](#datatypeid) | false |
| [locationid](#locationid) | false |
| [stationid](#stationid) | false |
| [startdate](#date) | true |
| [enddate](#date) | true |
| [includemetadata](#includemetadata) | false |
| [units](#units) | false |
| [sortfield](#sortfield) | false |
| [sortorder](#sortorder) | false |
| [limit](#limit) | false |
| [offset](#offset) | false |

# __**Params**__
---
## datasetid
| id | name | mindate | maxdate |
| ----------- | ----------- | ----------- | ----------- |
| GHCND | Daily Summaries | 1763-01-01 | 2022-04-11 |
| GSOM | Global Summary of the Month | 1763-01-01 | 2022-04-01 |
| GSOY | Global Summary of the Year | 1763-01-01 | 2022-01-01 |
| NEXRAD2 | Weather Radar (Level II) | 1991-06-05 | 2022-04-11 |
| NEXRAD3 | Weather Radar (Level III) | 1994-05-20 | 2022-04-11 |
| NORMAL_ANN | Normals Annual/Seasonal | 2010-01-01 | 2010-01-01 |
| NORMAL_DLY | Normals Daily | 2010-01-01 | 2010-12-31 |
| NORMAL_HLY | Normals Hourly | 2010-01-01 | 2010-12-31 |
| NORMAL_MLY | Normals Monthly | 2010-01-01 | 2010-12-01 |
| PRECIP_15 | Precipitation 15 Minute | 1970-05-12 | 2014-01-01 |
| PRECIP_HLY | Precipitation Hourly | 1900-01-01 | 2014-01-01 |

## datacategoryid

| id | name |
| ----------- | ----------- |
| ANNAGR | Annual Agricultural |
| ANNDD | Annual Degree Days |
| ANNPRCP | Annual Precipitation |
| ANNTEMP | Annual Temperature |
| AUAGR | Autumn Agricultural |
| AUDD | Autumn Degree Days |
| AUPRCP | Autumn Precipitation |
| AUTEMP | Autumn Temperature |
| COMP | Computed |
| COMPAGR | Computed Agricultural |
| DD | Degree Days |
| DUALPOLMOMENT | Dual-Pol Moments |
| ECHOTOP | Echo Tops |
| EVAP | Evaporation |
| HYDROMETEOR | Hydrometeor Type |
| LAND | Land |
| MISC | Miscellany |
| OTHER | Other |
| OVERLAY | Overlay |
| PRCP | Precipitation |
| PRES | Pressure |
| REFLECTIVITY | Reflectivity |
| SKY | Sky cover & clouds |
| SPAGR | Spring Agricultural |
| SPDD | Spring Degree Days |
| SPPRCP | Spring Precipitation |
| SPTEMP | Spring Temperature |
| SUAGR | Summer Agricultural |
| SUDD | Summer Degree Days |
| SUN | Sunshine |
| SUPRCP | Summer Precipitation |
| SUTEMP | Summer Temperature |
| TEMP | Air Temperature |
| VELOCITY | Velocity |
| VERTINTLIQUID | Vertical Integrated Liquid |
| WATER | Water |
| WIAGR | Winter Agricultural |
| WIDD | Winter Degree Days |
| WIND | Wind |
| WIPRCP | Winter Precipitation |
| WITEMP | Winter Temperature |
| WXTYPE | Weather Type |

## locationcategoryid

| id | name |
| ----------- | ----------- |
| CITY | City |
| CLIM_DIV | Climate Division |
| CLIM_REG | Climate Region |
| CNTRY | Country |
| CNTY | County |
| HYD_ACC | Hydrologic Accounting Unit |
| HYD_CAT | Hydrologic Cataloging Unit |
| HYD_REG | Hydrologic Region |
| HYD_SUB | Hydrologic Subregion |
| ST | State |
| US_TERR | US Territory |
| ZIP | Zip Code |

## datatypeid

There are more than 1565 datatypeid, i will make a search engine to easily find the id
For the moment, a short list of "important" datatypeid : 
| id | name |
| ----------- | ----------- |
| ALL | Base Data |
| ACMC | Average cloudiness midnight to midnight from 30-second ceilometer data |
| ACSC | Average cloudiness sunrise to sunset from 30-second ceilometer data |
| ANN-CLDD-NORMAL | Long-term averages of annual cooling degree days with base 65F |
| ANN-DUTR-NORMAL | Long-term averages of annual diurnal temperature range |
| ANN-GRDD-BASE65 | Long-term averages of annual growing degree days with base 65F |
| ANN-HTDD-NORMAL | Long-term averages of annual heating degree days with base 65F |
| ANN-PRCP-NORMAL | Long-term averages of annual precipitation totals |
| ANN-SNOW-NORMAL | Long-term averages of annual snowfall totals |
| ANN-TAVG-NORMAL | Long-term averages of annual average temperature |
| ANN-TMAX-NORMAL | Long-term averages of annual maximum temperature |
| AWND | Average wind speed |
| MMNT | Monthly Mean minimum temperature |
| MMXT | Monthly Mean maximum temperature |
| MXSD | Maximum snow depth |
| PRCP | Precipitation |
| RCM | Radar Coded Message |

## stationid

There are more than 150 000 stationid !
I will do a map & function to design 2 points, every stations in the square will be added to the stationid.

## limit

Results limit can be ajusted between 0 and 1000.
Defaults to `25`

## date

A valid ISO formated date `YYYY-MM-DD` (1970-10-03) or date time `YYYY-MM-DDThh:mm:ss` (1970-10-03T09:23:41)

## locationid

The id format is : CITY:{first2lettersOfCountryName}{townID?}
For example Vianna in Austria has this id : `CITY:AU000006`
I will create an interactive map to get those ID easily

## offset

The offset define the starting place where we have to get result.
For example, we have 38862 results but we are limited to request 1000 results at once, to get the 1000 next results we have to increment the offset by 1000.
Defaults to `0`

## sortfield

The field to sort results by, it supports `id`, `name`, `mindate`, `maxdate`, `datacoverage `

## sortorder

The order to sort by, it can be `asc` or `desc`.
Defaults to `asc`

## unit

Will scale & convert the data to the specified unit, it can be `standart` or `metric`.

## includemetadata

Decide to get the metadata or not. (Improve response time)
Defaults to `true`

## extent

The desired geographical extent for search, can be generated by `LatLngBounds.toUrlValue` from [Google Maps API V3](https://developers.google.com/maps/documentation/javascript/reference#LatLngBounds)
