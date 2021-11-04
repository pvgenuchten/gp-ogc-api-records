## 1. Data provider

GeoNetwork Community - Titellus

## 2. Thematic scope

Discovery

## 3. Envisaged use

The API is a demo

## 4. Requirements classes

OGC conformance classes:

- http://www.opengis.net/spec/ogcapi-records-1/1.0/conf/core
- http://www.opengis.net/spec/ogcapi-records-1/1.0/conf/iso19139
- http://www.opengis.net/spec/ogcapi-records-1/1.0/conf/geojson

Requirements classes implemented from the Good Practice:

- http://inspire.ec.europa.eu/id/spec/ogc-api-records/1.0/req/discovery

## 5. Server-side technology

- [GeoNetwork Microservices](https://github.com/geonetwork/geonetwork-microservices/tree/main/modules/services/ogc-api-records)
- Elastic Search
- PostGreSQL

## 6. Endpoints and client applications

Endpoint: 

https://apps.titellus.net/ogcapi/collections/main/items

## 7. Issues

- Service does not support the geojson output yet, instead it renders a random json output

## Additional information


