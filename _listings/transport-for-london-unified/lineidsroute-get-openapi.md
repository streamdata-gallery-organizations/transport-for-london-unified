---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Line s  Route
  description: Get all valid routes for given line ids, including the name and id
    of the originating and terminating stops for each route..
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
  /Journey/JourneyResults/{from}/to/{to}:
    get:
      summary: Journey  Journey Results from to to
      description: Perform a journey planner search from the parameters specified
        in simple types.
      operationId: Journey_JourneyResults
      x-api-path-slug: journeyjourneyresultsfromtoto-get
      parameters:
      - in: query
        name: accessibilityPreference
        description: The accessibility preference must be a comma separated list eg
      - in: query
        name: adjustment
        description: Time adjustment command
      - in: query
        name: alternativeCycle
        description: Option to determine whether to return alternative cycling journey
      - in: query
        name: alternativeWalking
        description: Option to determine whether to return alternative walking journey
      - in: query
        name: applyHtmlMarkup
        description: Flag to determine whether certain text (e
      - in: query
        name: bikeProficiency
        description: A comma separated list of cycling proficiency levels
      - in: query
        name: cyclePreference
        description: The cycle preference
      - in: query
        name: date
        description: The date must be in yyyyMMdd format
      - in: path
        name: from
        description: Origin of the journey
      - in: query
        name: fromName
        description: An optional name to associate with the origin of the journey
          in the results
      - in: query
        name: journeyPreference
        description: 'The journey preference eg possible options: leastinterchange
          | leasttime | leastwalking'
      - in: query
        name: maxTransferMinutes
        description: The max walking time in minutes for transfer eg
      - in: query
        name: maxWalkingMinutes
        description: The max walking time in minutes for journeys eg
      - in: query
        name: mode
        description: The mode must be a comma separated list of modes
      - in: query
        name: nationalSearch
        description: Does the journey cover stops outside London? eg
      - in: query
        name: taxiOnlyTrip
        description: A boolean to indicate whether to return one or more taxi journeys
      - in: query
        name: time
        description: The time must be in HHmm format
      - in: query
        name: timeIs
        description: 'Does the time given relate to arrival or leaving time? Possible
          options: departing | arriving'
      - in: path
        name: to
        description: Destination of the journey
      - in: query
        name: toName
        description: An optional name to associate with the destination of the journey
          in the results
      - in: query
        name: useMultiModalCall
        description: A boolean to indicate whether or not to return 3 public transport
          journeys, a bus journey, a cycle hire journey, a personal cycle journey
          and a walking journey
      - in: query
        name: via
        description: Travel through point on the journey
      - in: query
        name: viaName
        description: An optional name to associate with the via point of the journey
          in the results
      - in: query
        name: walkingOptimization
        description: A boolean to indicate whether to optimize journeys using walking
      - in: query
        name: walkingSpeed
        description: The walking speed
      responses:
        200:
          description: OK
      tags:
      - Journey
      - ""
      - Journey
      - Results
      - From
      - To
      - To
  /Journey/Meta/Modes:
    get:
      summary: Journey  Meta  Modes
      description: Gets a list of all of the available journey planner modes.
      operationId: Journey_Meta
      x-api-path-slug: journeymetamodes-get
      responses:
        200:
          description: OK
      tags:
      - Journey
      - ""
      - Meta
      - ""
      - Modes
  /Line/Meta/DisruptionCategories:
    get:
      summary: Line  Meta  Disruption Categories
      description: Gets a list of valid disruption categories.
      operationId: Line_MetaDisruptionCategories
      x-api-path-slug: linemetadisruptioncategories-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Disruption
      - Categories
  /Line/Meta/Modes:
    get:
      summary: Line  Meta  Modes
      description: Gets a list of valid modes.
      operationId: Line_MetaModes
      x-api-path-slug: linemetamodes-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Modes
  /Line/Meta/ServiceTypes:
    get:
      summary: Line  Meta  Service Types
      description: Gets a list of valid servicetypes to filter on.
      operationId: Line_MetaServiceTypes
      x-api-path-slug: linemetaservicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Service
      - Types
  /Line/Meta/Severity:
    get:
      summary: Line  Meta  Severity
      description: Gets a list of valid severity codes.
      operationId: Line_MetaSeverity
      x-api-path-slug: linemetaseverity-get
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Meta
      - ""
      - Severity
  /Line/Mode/{modes}:
    get:
      summary: Line  Mode modes
      description: Gets lines that serve the given modes..
      operationId: Line_GetByMode
      x-api-path-slug: linemodemodes-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
  /Line/Mode/{modes}/Disruption:
    get:
      summary: Line  Mode modes  Disruption
      description: Get disruptions for all lines of the given modes..
      operationId: Line_DisruptionByMode
      x-api-path-slug: linemodemodesdisruption-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Disruption
  /Line/Mode/{modes}/Route:
    get:
      summary: Line  Mode modes  Route
      description: Gets all lines and their valid routes for given modes, including
        the name and id of the originating and terminating stops for each route.
      operationId: Line_RouteByMode
      x-api-path-slug: linemodemodesroute-get
      parameters:
      - in: path
        name: modes
        description: A comma-separated list of modes e
      - in: query
        name: serviceTypes
        description: A comma seperated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Route
  /Line/Mode/{modes}/Status:
    get:
      summary: Line  Mode modes  Status
      description: Gets the line status of for all lines for the given modes.
      operationId: Line_StatusByMode
      x-api-path-slug: linemodemodesstatus-get
      parameters:
      - in: query
        name: detail
        description: Include details of the disruptions that are causing the line
          status including the affected stops and routes
      - in: path
        name: modes
        description: A comma-separated list of modes to filter by
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Mode
      - Modes
      - ""
      - Status
  /Line/Route:
    get:
      summary: Line  Route
      description: Get all valid routes for all lines, including the name and id of
        the originating and terminating stops for each route..
      operationId: Line_Route
      x-api-path-slug: lineroute-get
      parameters:
      - in: query
        name: serviceTypes
        description: A comma seperated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Route
  /Line/Search/{query}:
    get:
      summary: Line  Search query
      description: Search for lines or routes matching the query string.
      operationId: Line_Search
      x-api-path-slug: linesearchquery-get
      parameters:
      - in: query
        name: modes
        description: Optionally filter by the specified modes
      - in: path
        name: query
        description: Search term e
      - in: query
        name: serviceTypes
        description: A comma seperated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Search
      - Query
  /Line/Status/{severity}:
    get:
      summary: Line  Status severity
      description: "Gets the line status for all lines with a given severity\r\n            a
        list of valid severity codes can be obtained from a call to line/meta/severity."
      operationId: Line_StatusBySeverity
      x-api-path-slug: linestatusseverity-get
      parameters:
      - in: path
        name: severity
        description: 'The level of severity (eg: a number from 0 to 14)'
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Status
      - Severity
  /Line/{ids}:
    get:
      summary: Line s
      description: Gets lines that match the specified line ids..
      operationId: Line_Get
      x-api-path-slug: lineids-get
      parameters:
      - in: path
        name: ids
        description: A comma-separated list of line ids e
      responses:
        200:
          description: OK
      tags:
      - Line
      - S
  /Line/{ids}/Arrivals/{stopPointId}:
    get:
      summary: Line s  Arrivals stop Point Id
      description: Get the list of arrival predictions for given line ids based at
        the given stop.
      operationId: Line_Arrivals
      x-api-path-slug: lineidsarrivalsstoppointid-get
      parameters:
      - in: query
        name: destinationStationId
        description: Optional
      - in: query
        name: direction
        description: Optional
      - in: path
        name: ids
        description: A comma-separated list of line ids e
      - in: path
        name: stopPointId
        description: Optional
      responses:
        200:
          description: OK
      tags:
      - Line
      - S
      - ""
      - Arrivals
      - Stop
      - Point
      - Id
  /Line/{ids}/Disruption:
    get:
      summary: Line s  Disruption
      description: Get disruptions for the given line ids.
      operationId: Line_Disruption
      x-api-path-slug: lineidsdisruption-get
      parameters:
      - in: path
        name: ids
        description: A comma-separated list of line ids e
      responses:
        200:
          description: OK
      tags:
      - Line
      - S
      - ""
      - Disruption
  /Line/{ids}/Route:
    get:
      summary: Line s  Route
      description: Get all valid routes for given line ids, including the name and
        id of the originating and terminating stops for each route..
      operationId: Line_LineRoutesByIds
      x-api-path-slug: lineidsroute-get
      parameters:
      - in: path
        name: ids
        description: A comma-separated list of line ids e
      - in: query
        name: serviceTypes
        description: A comma seperated list of service types to filter on
      responses:
        200:
          description: OK
      tags:
      - Line
      - S
      - ""
      - Route
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