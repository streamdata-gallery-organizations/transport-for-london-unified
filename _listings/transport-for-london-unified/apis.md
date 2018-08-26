---
name: Transport for London Unified
x-slug: transport-for-london-unified
description: We are the integrated transport authority responsible for delivering
  Mayor of London Sadiq Khans strategy and commitments on transport. We run the day-to-day
  operation of the Capitals public transport network and manage Londons main roads.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Transport for London Unified
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/apis.md
specificationVersion: "0.14"
apis:
- name: Transport for London Unified - Accent Stats year
  x-api-slug: accidentstatsyear-get
  description: Gets all accident details for accidents occuring in the specified year.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/accidentstatsyear-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/accidentstatsyear-get-openapi.md
- name: Transport for London Unified - Air Quality
  x-api-slug: airquality-get
  description: Gets air quality data feed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/airquality-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/airquality-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepoint-get
  description: "Gets all bike point locations. the place object has an addtionalproperties
    array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers
    which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks
    - (nbbikes + nbspa."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/bikepoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/bikepoint-get-openapi.md
- name: Transport for London Unified - Bike Point  Search
  x-api-slug: bikepointsearch-get
  description: "Search for bike stations by their name, a bike point's name often
    contains information about the name of the street\r\n            or nearby landmarks,
    for example. note that the search result does not contain the placeproperties
    i.e. the status\r\n     ."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/bikepointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/bikepointsearch-get-openapi.md
- name: Transport for London Unified - Bike Point
  x-api-slug: bikepointid-get
  description: Gets the bike point with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/bikepointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/bikepointid-get-openapi.md
- name: Transport for London Unified - Cabwise search
  x-api-slug: cabwisesearch-get
  description: Gets taxis and minicabs contact information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/cabwisesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/cabwisesearch-get-openapi.md
- name: Transport for London Unified - Journey  Journey Results from to to
  x-api-slug: journeyjourneyresultsfromtoto-get
  description: Perform a journey planner search from the parameters specified in simple
    types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/journeyjourneyresultsfromtoto-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/journeyjourneyresultsfromtoto-get-openapi.md
- name: Transport for London Unified - Journey  Meta  Modes
  x-api-slug: journeymetamodes-get
  description: Gets a list of all of the available journey planner modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/journeymetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/journeymetamodes-get-openapi.md
- name: Transport for London Unified - Line  Meta  Disruption Categories
  x-api-slug: linemetadisruptioncategories-get
  description: Gets a list of valid disruption categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetadisruptioncategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetadisruptioncategories-get-openapi.md
- name: Transport for London Unified - Line  Meta  Modes
  x-api-slug: linemetamodes-get
  description: Gets a list of valid modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetamodes-get-openapi.md
- name: Transport for London Unified - Line  Meta  Service Types
  x-api-slug: linemetaservicetypes-get
  description: Gets a list of valid servicetypes to filter on.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetaservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetaservicetypes-get-openapi.md
- name: Transport for London Unified - Line  Meta  Severity
  x-api-slug: linemetaseverity-get
  description: Gets a list of valid severity codes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetaseverity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemetaseverity-get-openapi.md
- name: Transport for London Unified - Line  Mode modes
  x-api-slug: linemodemodes-get
  description: Gets lines that serve the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodes-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Disruption
  x-api-slug: linemodemodesdisruption-get
  description: Get disruptions for all lines of the given modes..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Route
  x-api-slug: linemodemodesroute-get
  description: Gets all lines and their valid routes for given modes, including the
    name and id of the originating and terminating stops for each route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodesroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodesroute-get-openapi.md
- name: Transport for London Unified - Line  Mode modes  Status
  x-api-slug: linemodemodesstatus-get
  description: Gets the line status of for all lines for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodesstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linemodemodesstatus-get-openapi.md
- name: Transport for London Unified - Line  Route
  x-api-slug: lineroute-get
  description: Get all valid routes for all lines, including the name and id of the
    originating and terminating stops for each route..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineroute-get-openapi.md
- name: Transport for London Unified - Line  Search query
  x-api-slug: linesearchquery-get
  description: Search for lines or routes matching the query string.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linesearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linesearchquery-get-openapi.md
- name: Transport for London Unified - Line  Status severity
  x-api-slug: linestatusseverity-get
  description: "Gets the line status for all lines with a given severity\r\n            a
    list of valid severity codes can be obtained from a call to line/meta/severity."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linestatusseverity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/linestatusseverity-get-openapi.md
- name: Transport for London Unified - Line s
  x-api-slug: lineids-get
  description: Gets lines that match the specified line ids..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineids-get-openapi.md
- name: Transport for London Unified - Line s  Arrivals stop Point Id
  x-api-slug: lineidsarrivalsstoppointid-get
  description: Get the list of arrival predictions for given line ids based at the
    given stop.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsarrivalsstoppointid-get-openapi.md
- name: Transport for London Unified - Line s  Disruption
  x-api-slug: lineidsdisruption-get
  description: Get disruptions for the given line ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsdisruption-get-openapi.md
- name: Transport for London Unified - Line s  Route
  x-api-slug: lineidsroute-get
  description: Get all valid routes for given line ids, including the name and id
    of the originating and terminating stops for each route..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsroute-get-openapi.md
- name: Transport for London Unified - Line s  Status
  x-api-slug: lineidsstatus-get
  description: Gets the line status of for given line ids e.g minor delays.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsstatus-get-openapi.md
- name: Transport for London Unified - Line s  Status  Start Date to  End Date
  x-api-slug: lineidsstatusstartdatetoenddate-get
  description: Gets the line status for given line ids during the provided dates e.g
    minor delays.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsstatusstartdatetoenddate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsstatusstartdatetoenddate-get-openapi.md
- name: Transport for London Unified - Line  Route  Sequence direction
  x-api-slug: lineidroutesequencedirection-get
  description: Gets all valid routes for given line id, including the sequence of
    stops on each route..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidroutesequencedirection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidroutesequencedirection-get-openapi.md
- name: Transport for London Unified - Line  Stop Points
  x-api-slug: lineidstoppoints-get
  description: Gets a list of the stations that serve the given line id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidstoppoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidstoppoints-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id
  x-api-slug: lineidtimetablefromstoppointid-get
  description: Gets the timetable for a specified station on the give line.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointid-get-openapi.md
- name: Transport for London Unified - Line  Timetable from Stop Point Id to to Stop
    Point Id
  x-api-slug: lineidtimetablefromstoppointidtotostoppointid-get
  description: Gets the timetable for a specified station on the give line with specified
    destination.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidtimetablefromstoppointidtotostoppointid-get-openapi.md
- name: Transport for London Unified - Mode  Active Service Types
  x-api-slug: modeactiveservicetypes-get
  description: "Returns the service type active for a mode.\r\n            currently
    only supports tube."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/modeactiveservicetypes-get-openapi.md
- name: Transport for London Unified - Mode mode  Arrivals
  x-api-slug: modemodearrivals-get
  description: Gets the next arrival predictions for all stops of a given mode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/modemodearrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/modemodearrivals-get-openapi.md
- name: Transport for London Unified - Occupancy  Bike Points s
  x-api-slug: occupancybikepointsids-get
  description: Get the occupancy for bike points..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancybikepointsids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancybikepointsids-get-openapi.md
- name: Transport for London Unified - Occupancy  Car Park
  x-api-slug: occupancycarpark-get
  description: Gets the occupancy for all car parks that have occupancy data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancycarpark-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancycarpark-get-openapi.md
- name: Transport for London Unified - Occupancy  Car Park
  x-api-slug: occupancycarparkid-get
  description: Gets the occupancy for a car park with a given id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancycarparkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancycarparkid-get-openapi.md
- name: Transport for London Unified - Occupancy  Charge Connector
  x-api-slug: occupancychargeconnector-get
  description: Gets the occupancy for all charge connectors.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancychargeconnector-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancychargeconnector-get-openapi.md
- name: Transport for London Unified - Occupancy  Charge Connector s
  x-api-slug: occupancychargeconnectorids-get
  description: Gets the occupancy for a charge connectors with a given id (sourcesystemplaceid).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancychargeconnectorids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/occupancychargeconnectorids-get-openapi.md
- name: Transport for London Unified - Place
  x-api-slug: place-get
  description: "Gets the places that lie within the bounding box defined by the lat/lon
    of its north-west and south-east corners. optionally filters\r\n            on
    type and can strip properties for a smaller payload.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/place-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/place-get-openapi.md
- name: Transport for London Unified - Place  Address  Streets  Postcode
  x-api-slug: placeaddressstreetspostcode-get
  description: Gets the set of streets associated with a post code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placeaddressstreetspostcode-get-openapi.md
- name: Transport for London Unified - Place  Meta  Categories
  x-api-slug: placemetacategories-get
  description: Gets a list of all of the available place property categories and keys..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placemetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placemetacategories-get-openapi.md
- name: Transport for London Unified - Place  Meta  Place Types
  x-api-slug: placemetaplacetypes-get
  description: Gets a list of the available types of place..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placemetaplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placemetaplacetypes-get-openapi.md
- name: Transport for London Unified - Place  Search
  x-api-slug: placesearch-get
  description: Gets all places that matches the given query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placesearch-get-openapi.md
- name: Transport for London Unified - Place  Type types
  x-api-slug: placetypetypes-get
  description: Gets all places of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placetypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placetypetypes-get-openapi.md
- name: Transport for London Unified - Place
  x-api-slug: placeid-get
  description: Gets the place with the given id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placeid-get-openapi.md
- name: Transport for London Unified - Place type  At  Lat  Lon
  x-api-slug: placetypeatlatlon-get
  description: "Gets any places of the given type whose geography intersects the given
    latitude and longitude. in practice this means the place\r\n            must be
    polygonal e.g. a boroughboundary.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placetypeatlatlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placetypeatlatlon-get-openapi.md
- name: Transport for London Unified - Place type overlay z  Lat  Lon wth height
  x-api-slug: placetypeoverlayzlatlonwidthheight-get
  description: Gets the place overlay for a given set of co-ordinates and a given
    width/height..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/placetypeoverlayzlatlonwidthheight-get-openapi.md
- name: Transport for London Unified - Road
  x-api-slug: road-get
  description: Gets all roads managed by tfl.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/road-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/road-get-openapi.md
- name: Transport for London Unified - Road  Meta  Categories
  x-api-slug: roadmetacategories-get
  description: Gets a list of valid roaddisruption categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadmetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadmetacategories-get-openapi.md
- name: Transport for London Unified - Road  Meta  Severities
  x-api-slug: roadmetaseverities-get
  description: Gets a list of valid roaddisruption severity codes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadmetaseverities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadmetaseverities-get-openapi.md
- name: Transport for London Unified - Road all  Disruption disruption Ids
  x-api-slug: roadalldisruptiondisruptionids-get
  description: Gets a list of active disruptions filtered by disruption ids..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadalldisruptiondisruptionids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadalldisruptiondisruptionids-get-openapi.md
- name: Transport for London Unified - Road all  Street  Disruption
  x-api-slug: roadallstreetdisruption-get
  description: Gets a list of disrupted streets. if no date filters are provided,
    current disruptions are returned..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadallstreetdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadallstreetdisruption-get-openapi.md
- name: Transport for London Unified - Road s
  x-api-slug: roadids-get
  description: Gets the road with the specified id (e.g. a1).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadids-get-openapi.md
- name: Transport for London Unified - Road s  Disruption
  x-api-slug: roadidsdisruption-get
  description: Get active disruptions, filtered by road ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadidsdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadidsdisruption-get-openapi.md
- name: Transport for London Unified - Road s  Status
  x-api-slug: roadidsstatus-get
  description: Gets the specified roads with the status aggregated over the date range
    specified, or now until the end of today if no dates are passed..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadidsstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/roadidsstatus-get-openapi.md
- name: Transport for London Unified - Search
  x-api-slug: search-get
  description: "Search the site for occurrences of the query string. the maximum number
    of results returned is equal to the maximum page size\r\n            of 100. to
    return subsequent pages, use the paginated overload.."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/search-get-openapi.md
- name: Transport for London Unified - Search  Bus Schedules
  x-api-slug: searchbusschedules-get
  description: Searches the bus schedules folder on s3 for a given bus number..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchbusschedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchbusschedules-get-openapi.md
- name: Transport for London Unified - Search  Meta  Categories
  x-api-slug: searchmetacategories-get
  description: Gets the available search categories..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchmetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchmetacategories-get-openapi.md
- name: Transport for London Unified - Search  Meta  Search Provers
  x-api-slug: searchmetasearchproviders-get
  description: Gets the available searchprovider names..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchmetasearchproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchmetasearchproviders-get-openapi.md
- name: Transport for London Unified - Search  Meta  Sorts
  x-api-slug: searchmetasorts-get
  description: Gets the available sorting options..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchmetasorts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/searchmetasorts-get-openapi.md
- name: Transport for London Unified - Stop Point
  x-api-slug: stoppoint-get
  description: Gets a list of stoppoints within {radius} by the specified criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppoint-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Categories
  x-api-slug: stoppointmetacategories-get
  description: Gets the list of available stoppoint additional information categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmetacategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmetacategories-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Modes
  x-api-slug: stoppointmetamodes-get
  description: Gets the list of available stoppoint modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmetamodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmetamodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Meta  Stop Types
  x-api-slug: stoppointmetastoptypes-get
  description: Gets the list of available stoppoint types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmetastoptypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes
  x-api-slug: stoppointmodemodes-get
  description: Gets a list of stoppoints filtered by the modes available at that stoppoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmodemodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmodemodes-get-openapi.md
- name: Transport for London Unified - Stop Point  Mode modes  Disruption
  x-api-slug: stoppointmodemodesdisruption-get
  description: Gets a distinct list of disrupted stop points for the given modes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointmodemodesdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Search
  x-api-slug: stoppointsearch-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointsearch-get-openapi.md
- name: Transport for London Unified - Stop Point  Search query
  x-api-slug: stoppointsearchquery-get
  description: Search stoppoints by their common name, or their 5-digit countdown
    bus stop code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointsearchquery-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointsearchquery-get-openapi.md
- name: Transport for London Unified - Stop Point  Service Types
  x-api-slug: stoppointservicetypes-get
  description: Gets the service types for a given stoppoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointservicetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointservicetypes-get-openapi.md
- name: Transport for London Unified - Stop Point  Sms
  x-api-slug: stoppointsmsid-get
  description: Gets a stoppoint for a given sms code..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointsmsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointsmsid-get-openapi.md
- name: Transport for London Unified - Stop Point  Type types
  x-api-slug: stoppointtypetypes-get
  description: Gets all stop points of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointtypetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointtypetypes-get-openapi.md
- name: Transport for London Unified - Stop Point s
  x-api-slug: stoppointids-get
  description: Gets a list of stoppoints corresponding to the given list of stop ids..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointids-get-openapi.md
- name: Transport for London Unified - Stop Point s  Disruption
  x-api-slug: stoppointidsdisruption-get
  description: Gets all disruptions for the specified stoppointid, plus disruptions
    for any child naptan records it may have..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidsdisruption-get-openapi.md
- name: Transport for London Unified - Stop Point  Arrivals
  x-api-slug: stoppointidarrivals-get
  description: Gets the list of arrival predictions for the given stop point id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidarrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidarrivals-get-openapi.md
- name: Transport for London Unified - Stop Point  Can Reach On Line line Id
  x-api-slug: stoppointidcanreachonlinelineid-get
  description: Gets stopoints that are reachable from a station/line combination..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidcanreachonlinelineid-get-openapi.md
- name: Transport for London Unified - Stop Point  Crowding line
  x-api-slug: stoppointidcrowdingline-get
  description: Gets all the crowding data (static) for the stoppointid, plus crowding
    data for a given line and optionally a particular direction..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidcrowdingline-get-openapi.md
- name: Transport for London Unified - Stop Point  Direction To to Stop Point Id
  x-api-slug: stoppointiddirectiontotostoppointid-get
  description: Returns the canonical direction, "inbound" or "outbound", for a given
    pair of stop point ids in the direction from -&gt; to..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointiddirectiontotostoppointid-get-openapi.md
- name: Transport for London Unified - Stop Point  Route
  x-api-slug: stoppointidroute-get
  description: Returns the route sections for all the lines that service the given
    stop point ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidroute-get-openapi.md
- name: Transport for London Unified - Stop Point place Types
  x-api-slug: stoppointidplacetypes-get
  description: Get a list of places corresponding to a given id and place types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointidplacetypes-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Car Parks
  x-api-slug: stoppointstoppointidcarparks-get
  description: Get car parks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointstoppointidcarparks-get-openapi.md
- name: Transport for London Unified - Stop Point stop Point Id  Taxi Ranks
  x-api-slug: stoppointstoppointidtaxiranks-get
  description: Gets a list of taxi ranks corresponding to the given stop point id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/stoppointstoppointidtaxiranks-get-openapi.md
- name: Transport for London Unified - Travel Times compare Overlay z mapcenter map
    Center Lat map Center Lon pinlocation pin Lat pin Lon dimensions wth height
  x-api-slug: traveltimescompareoverlayzmapcentermapcenterlatmapcenterlonpinlocationpinlatpinlondimensionswidthheight-get
  description: Gets the traveltime overlay..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/traveltimescompareoverlayzmapcentermapcenterlatmapcenterlonpinlocationpinlatpinlondimensionswidthheight-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/traveltimescompareoverlayzmapcentermapcenterlatmapcenterlonpinlocationpinlatpinlondimensionswidthheight-get-openapi.md
- name: Transport for London Unified - Travel Times overlay z mapcenter map Center
    Lat map Center Lon pinlocation pin Lat pin Lon dimensions wth height
  x-api-slug: traveltimesoverlayzmapcentermapcenterlatmapcenterlonpinlocationpinlatpinlondimensionswidthheight-get
  description: Gets the traveltime overlay..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/traveltimesoverlayzmapcentermapcenterlatmapcenterlonpinlocationpinlatpinlondimensionswidthheight-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/traveltimesoverlayzmapcentermapcenterlatmapcenterlonpinlocationpinlatpinlondimensionswidthheight-get-openapi.md
- name: Transport for London Unified - Vehicle  Emission Surcharge
  x-api-slug: vehicleemissionsurcharge-get
  description: Gets the emissions surcharge compliance for the vehicle.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/vehicleemissionsurcharge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/vehicleemissionsurcharge-get-openapi.md
- name: Transport for London Unified - Vehicle  Ulez Compliance
  x-api-slug: vehicleulezcompliance-get
  description: Gets the ulez surcharge compliance for the vehicle.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/vehicleulezcompliance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/vehicleulezcompliance-get-openapi.md
- name: Transport for London Unified - Vehicle s  Arrivals
  x-api-slug: vehicleidsarrivals-get
  description: Gets the predictions for a given list of vehicle id's..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/vehicleidsarrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/vehicleidsarrivals-get-openapi.md
- name: Transport for London Unified - Line s  Arrivals
  x-api-slug: lineidsarrivals-get
  description: Get the list of arrival predictions for given line ids based at the
    given stop.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transport-for-london-unified-api.png
  humanURL: https://tfl.gov.uk/
  baseURL: https://api.tfl.gov.uk//
  tags: Transportation, Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsarrivals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transport-for-london-unified/master/_listings/transport-for-london-unified/lineidsarrivals-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://transitfeeds.api.gallery.streamdata.io
- type: x-api-stack
  url: http://transport.for.london.unified.stack.network
- type: x-developer
  url: http://api.tfl.gov.uk
- type: x-website
  url: https://tfl.gov.uk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---