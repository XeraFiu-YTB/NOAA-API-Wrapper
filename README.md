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
| locationid | false |
| stationid | false |
| startdate | false |
| enddate | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |

## **__datatypes__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| locationid | false |
| stationid | false |
| datacategoryid | false |
| startdate | false |
| enddate | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |

## **__datasets__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| locationid | false |
| stationid | false |
| startdate | false |
| enddate | false |
| available | false |
| legacy | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |

## **__locationcategories__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| startdate | false |
| enddate | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |

## **__stations__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| locationid | false |
| datacategoryid | false |
| datatypeid | false |
| extent | false |
| startdate | false |
| enddate | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |

## **__locations__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| locationcategoryid | false |
| parentid | false |
| startdate | false |
| enddate | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |

## **__data__**
| name | required |
| ----------- | ----------- |
| [datasetid](#datasetid) | false |
| datatypeid | false |
| locationid | false |
| stationid | false |
| startdate | true |
| enddate | true |
| includemetadata | false |
| units | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |

# __**Params**__
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
