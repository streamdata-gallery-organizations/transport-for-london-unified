---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Place type  At  Lat  Lon
  description: "Gets any places of the given type whose geography intersects the given
    latitude and longitude. in practice this means the place\r\n            must be
    polygonal e.g. a boroughboundary.."
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
  /Line/{ids}/Status:
    get:
      summary: Line s  Status
      description: Gets the line status of for given line ids e.g minor delays.
      operationId: Line_StatusByIds
      x-api-path-slug: lineidsstatus-get
      parameters:
      - in: query
        name: detail
        description: Include details of the disruptions that are causing the line
          status including the affected stops and routes
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
      - Status
  /Line/{ids}/Status/{StartDate}/to/{EndDate}:
    get:
      summary: Line s  Status  Start Date to  End Date
      description: Gets the line status for given line ids during the provided dates
        e.g minor delays.
      operationId: Line_Status
      x-api-path-slug: lineidsstatusstartdatetoenddate-get
      parameters:
      - in: query
        name: dateRange.endDate
      - in: query
        name: dateRange.startDate
      - in: query
        name: detail
        description: Include details of the disruptions that are causing the line
          status including the affected stops and routes
      - in: query
        name: endDate
      - in: path
        name: EndDate
      - in: path
        name: ids
        description: A comma-separated list of line ids e
      - in: query
        name: startDate
      - in: path
        name: StartDate
      responses:
        200:
          description: OK
      tags:
      - Line
      - S
      - ""
      - Status
      - ""
      - Start
      - Date
      - To
      - ""
      - End
      - Date
  /Line/{id}/Route/Sequence/{direction}:
    get:
      summary: Line  Route  Sequence direction
      description: Gets all valid routes for given line id, including the sequence
        of stops on each route..
      operationId: Line_RouteSequence
      x-api-path-slug: lineidroutesequencedirection-get
      parameters:
      - in: path
        name: direction
        description: The direction of travel
      - in: query
        name: excludeCrowding
        description: That excludes crowding from line disruptions
      - in: path
        name: id
        description: A single line id e
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
      - ""
      - Sequence
      - Direction
  /Line/{id}/StopPoints:
    get:
      summary: Line  Stop Points
      description: Gets a list of the stations that serve the given line id.
      operationId: Line_StopPoints
      x-api-path-slug: lineidstoppoints-get
      parameters:
      - in: path
        name: id
        description: A single line id e
      - in: query
        name: tflOperatedNationalRailStationsOnly
        description: If the national-rail line is requested, this flag will filter
          the national rail stations so that only those operated by TfL are returned
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Stop
      - Points
  /Line/{id}/Timetable/{fromStopPointId}:
    get:
      summary: Line  Timetable from Stop Point Id
      description: Gets the timetable for a specified station on the give line.
      operationId: Line_Timetable
      x-api-path-slug: lineidtimetablefromstoppointid-get
      parameters:
      - in: path
        name: fromStopPointId
        description: The originating stations stop point id (station naptan code e
      - in: path
        name: id
        description: A single line id e
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Timetable
      - From
      - Stop
      - Point
      - Id
  /Line/{id}/Timetable/{fromStopPointId}/to/{toStopPointId}:
    get:
      summary: Line  Timetable from Stop Point Id to to Stop Point Id
      description: Gets the timetable for a specified station on the give line with
        specified destination.
      operationId: Line_TimetableTo
      x-api-path-slug: lineidtimetablefromstoppointidtotostoppointid-get
      parameters:
      - in: path
        name: fromStopPointId
        description: The originating stations stop point id (station naptan code e
      - in: path
        name: id
        description: A single line id e
      - in: path
        name: toStopPointId
        description: The destination stationss Naptan code
      responses:
        200:
          description: OK
      tags:
      - Line
      - ""
      - Timetable
      - From
      - Stop
      - Point
      - Id
      - To
      - To
      - Stop
      - Point
      - Id
  /Mode/ActiveServiceTypes:
    get:
      summary: Mode  Active Service Types
      description: "Returns the service type active for a mode.\r\n            currently
        only supports tube."
      operationId: Mode_GetActiveServiceTypes
      x-api-path-slug: modeactiveservicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Mode
      - ""
      - Active
      - Service
      - Types
  /Mode/{mode}/Arrivals:
    get:
      summary: Mode mode  Arrivals
      description: Gets the next arrival predictions for all stops of a given mode.
      operationId: Mode_Arrivals
      x-api-path-slug: modemodearrivals-get
      parameters:
      - in: query
        name: count
        description: A number of arrivals to return for each stop, -1 to return all
          available
      - in: path
        name: mode
        description: A mode name e
      responses:
        200:
          description: OK
      tags:
      - Mode
      - Mode
      - ""
      - Arrivals
  /Occupancy/BikePoints/{ids}:
    get:
      summary: Occupancy  Bike Points s
      description: Get the occupancy for bike points..
      operationId: Occupancy_GetBikePointsOccupancies
      x-api-path-slug: occupancybikepointsids-get
      parameters:
      - in: path
        name: ids
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Bike
      - Points
      - S
  /Occupancy/CarPark:
    get:
      summary: Occupancy  Car Park
      description: Gets the occupancy for all car parks that have occupancy data.
      operationId: Occupancy.CarPark.get
      x-api-path-slug: occupancycarpark-get
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Car
      - Park
  /Occupancy/CarPark/{id}:
    get:
      summary: Occupancy  Car Park
      description: Gets the occupancy for a car park with a given id.
      operationId: Occupancy.CarPark.id.get
      x-api-path-slug: occupancycarparkid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Car
      - Park
  /Occupancy/ChargeConnector:
    get:
      summary: Occupancy  Charge Connector
      description: Gets the occupancy for all charge connectors.
      operationId: Occupancy_GetAllChargeConnectorStatus
      x-api-path-slug: occupancychargeconnector-get
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Charge
      - Connector
  /Occupancy/ChargeConnector/{ids}:
    get:
      summary: Occupancy  Charge Connector s
      description: Gets the occupancy for a charge connectors with a given id (sourcesystemplaceid).
      operationId: Occupancy_GetChargeConnectorStatus
      x-api-path-slug: occupancychargeconnectorids-get
      parameters:
      - in: path
        name: ids
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Charge
      - Connector
      - S
  /Place:
    get:
      summary: Place
      description: "Gets the places that lie within the bounding box defined by the
        lat/lon of its north-west and south-east corners. optionally filters\r\n            on
        type and can strip properties for a smaller payload.."
      operationId: Place_GetByGeoBox
      x-api-path-slug: place-get
      parameters:
      - in: query
        name: activeOnly
        description: An optional parameter to limit the results to active records
          only (Currently only the VariableMessageSign place type is supported)
      - in: query
        name: bbBoxpoints.neLat
      - in: query
        name: bbBoxpoints.neLon
      - in: query
        name: bbBoxpoints.swLat
      - in: query
        name: bbBoxpoints.swLon
      - in: query
        name: categories
        description: an optional list of comma separated property categories to return
          in the Places property bag
      - in: query
        name: includeChildren
        description: Defaults to false
      - in: query
        name: type
        description: place types to filter on, or null to return all types
      responses:
        200:
          description: OK
      tags:
      - Place
  /Place/Address/Streets/{Postcode}:
    get:
      summary: Place  Address  Streets  Postcode
      description: Gets the set of streets associated with a post code..
      operationId: Place_GetStreetsByPostCode
      x-api-path-slug: placeaddressstreetspostcode-get
      parameters:
      - in: query
        name: postcode
      - in: path
        name: Postcode
      - in: query
        name: postcodeInput.postcode
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Ress
      - ""
      - Streets
      - ""
      - Code
  /Place/Meta/Categories:
    get:
      summary: Place  Meta  Categories
      description: Gets a list of all of the available place property categories and
        keys..
      operationId: Place_MetaCategories
      x-api-path-slug: placemetacategories-get
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Meta
      - ""
      - Categories
  /Place/Meta/PlaceTypes:
    get:
      summary: Place  Meta  Place Types
      description: Gets a list of the available types of place..
      operationId: Place_MetaPlaceTypes
      x-api-path-slug: placemetaplacetypes-get
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Meta
      - ""
      - Place
      - Types
  /Place/Search:
    get:
      summary: Place  Search
      description: Gets all places that matches the given query.
      operationId: Place_Search
      x-api-path-slug: placesearch-get
      parameters:
      - in: query
        name: name
        description: The name of the place, you can use the /Place/Types/{types} endpoint
          to get a list of places for a given type including their names
      - in: query
        name: types
        description: A comma-separated list of the types to return
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Search
  /Place/Type/{types}:
    get:
      summary: Place  Type types
      description: Gets all places of a given type.
      operationId: Place_GetByType
      x-api-path-slug: placetypetypes-get
      parameters:
      - in: query
        name: activeOnly
        description: An optional parameter to limit the results to active records
          only (Currently only the VariableMessageSign place type is supported)
      - in: path
        name: types
        description: A comma-separated list of the types to return
      responses:
        200:
          description: OK
      tags:
      - Place
      - ""
      - Type
      - Types
  /Place/{id}:
    get:
      summary: Place
      description: Gets the place with the given id..
      operationId: Place_Get
      x-api-path-slug: placeid-get
      parameters:
      - in: path
        name: id
        description: The id of the place, you can use the /Place/Types/{types} endpoint
          to get a list of places for a given type including their ids
      - in: query
        name: includeChildren
        description: Defaults to false
      responses:
        200:
          description: OK
      tags:
      - Place
  /Place/{type}/At/{Lat}/{Lon}:
    get:
      summary: Place type  At  Lat  Lon
      description: "Gets any places of the given type whose geography intersects the
        given latitude and longitude. in practice this means the place\r\n            must
        be polygonal e.g. a boroughboundary.."
      operationId: Place_GetAt
      x-api-path-slug: placetypeatlatlon-get
      parameters:
      - in: query
        name: lat
      - in: path
        name: Lat
      - in: query
        name: location.lat
      - in: query
        name: location.lon
      - in: query
        name: lon
      - in: path
        name: Lon
      - in: path
        name: type
        description: The place type (a valid list of place types can be obtained from
          the /Place/Meta/placeTypes endpoint)
      responses:
        200:
          description: OK
      tags:
      - Place
      - Type
      - ""
      - At
      - ""
      - Lat
      - ""
      - Lon
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