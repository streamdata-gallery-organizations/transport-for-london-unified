---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Cabwise search
  description: Gets taxis and minicabs contact information.
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AccidentStats/{year}:
    get:
      summary: Accent Stats year
      description: Gets all accident details for accidents occuring in the specified
        year.
      operationId: AccidentStats_Get
      x-api-path-slug: accidentstatsyear-get
      parameters:
      - in: path
        name: year
        description: The year for which to filter the accidents on
      responses:
        200:
          description: OK
      tags:
      - Accent
      - Stats
      - Year
  /AirQuality:
    get:
      summary: Air Quality
      description: Gets air quality data feed.
      operationId: AirQuality_Get
      x-api-path-slug: airquality-get
      responses:
        200:
          description: OK
      tags:
      - Air
      - Quality
  /BikePoint:
    get:
      summary: Bike Point
      description: "Gets all bike point locations. the place object has an addtionalproperties
        array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers
        which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks
        - (nbbikes + nbspa."
      operationId: BikePoint_GetAll
      x-api-path-slug: bikepoint-get
      responses:
        200:
          description: OK
      tags:
      - Bike
      - Point
  /BikePoint/Search:
    get:
      summary: Bike Point  Search
      description: "Search for bike stations by their name, a bike point's name often
        contains information about the name of the street\r\n            or nearby
        landmarks, for example. note that the search result does not contain the placeproperties
        i.e. the status\r\n     ."
      operationId: BikePoint_Search
      x-api-path-slug: bikepointsearch-get
      parameters:
      - in: query
        name: query
        description: The search term e
      responses:
        200:
          description: OK
      tags:
      - Bike
      - Point
      - ""
      - Search
  /BikePoint/{id}:
    get:
      summary: Bike Point
      description: Gets the bike point with the given id..
      operationId: BikePoint_Get
      x-api-path-slug: bikepointid-get
      parameters:
      - in: path
        name: id
        description: A bike point id (a list of ids can be obtained from the above
          BikePoint call)
      responses:
        200:
          description: OK
      tags:
      - Bike
      - Point
  /Cabwise/search:
    get:
      summary: Cabwise search
      description: Gets taxis and minicabs contact information.
      operationId: Cabwise_Get
      x-api-path-slug: cabwisesearch-get
      parameters:
      - in: query
        name: forceXml
        description: Force Xml
      - in: query
        name: lat
        description: Latitude
      - in: query
        name: legacyFormat
        description: Legacy Format
      - in: query
        name: lon
        description: Longitude
      - in: query
        name: maxResults
        description: An optional parameter to limit the number of results return
      - in: query
        name: name
        description: Trading name of operating company
      - in: query
        name: optype
        description: Operator Type e
      - in: query
        name: radius
        description: The radius of the bounding circle in metres
      - in: query
        name: twentyFourSevenOnly
        description: Twenty Four Seven Only
      - in: query
        name: wc
        description: Wheelchair accessible
      responses:
        200:
          description: OK
      tags:
      - Cabwise
      - Search
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---