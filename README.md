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
| datasetid | false |
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
---
| datasetid | false |
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
---
| datatypeid | false |
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
---
| datasetid | false |
| startdate | false |
| enddate | false |
| sortfield | false |
| sortorder | false |
| limit | false |
| offset | false |
## **__stations__**
| name | required |
---
| datasetid | false |
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
---
| datasetid | false |
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
---
| datasetid | false |
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
