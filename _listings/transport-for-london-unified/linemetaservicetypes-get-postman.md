{
  "info": {
    "name": "Transport for London Unified Line  Meta  Service Types",
    "_postman_id": "c43f77d0-46ed-44c3-bdea-63b1870deb66",
    "description": "Gets a list of valid servicetypes to filter on.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accent",
      "item": [
        {
          "id": "1f4a3c58-0b65-4065-ac81-9cf5977fa6ae",
          "name": "AccidentStats_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "AccidentStats/:year"
              ],
              "variable": [
                {
                  "id": "year",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all accident details for accidents occuring in the specified year."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a90f8224-bfba-44ac-bfc8-a431c98cb500"
            }
          ]
        }
      ]
    },
    {
      "name": "Air",
      "item": [
        {
          "id": "7eb6e233-5b49-4d39-9b45-aab801aab4e2",
          "name": "AirQuality_Get",
          "request": {
            "url": "http://api.tfl.gov.uk/AirQuality",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets air quality data feed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2f88dbd-7b6c-4720-ae16-3775c8175ea4"
            }
          ]
        }
      ]
    },
    {
      "name": "Bike",
      "item": [
        {
          "id": "2f89a74d-6019-40cb-804c-35f603648bd0",
          "name": "BikePoint_GetAll",
          "request": {
            "url": "http://api.tfl.gov.uk/BikePoint",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets all bike point locations. the place object has an addtionalproperties array which contains the nbbikes, nbdocks and nbspaces\r\n            numbers which give the status of the bikepoint. a mismatch in these numbers i.e. nbdocks - (nbbikes + nbspa."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d0e8710-32ff-4444-b17a-b9f0a8cd3c48"
            }
          ]
        },
        {
          "id": "81f62d9a-28ad-4c48-90d2-16efdcc66def",
          "name": "BikePoint_Search",
          "request": {
            "url": "http://api.tfl.gov.uk/BikePoint/Search?query=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Search for bike stations by their name, a bike point's name often contains information about the name of the street\r\n            or nearby landmarks, for example. note that the search result does not contain the placeproperties i.e. the status\r\n     ."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d21eee7-4b99-41a3-a3d4-44e822b8b2c7"
            }
          ]
        },
        {
          "id": "96945d80-b5c8-4d18-a482-e5a2d134c67c",
          "name": "BikePoint_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "BikePoint/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the bike point with the given id.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e928f90-13da-465f-939e-a9b3a8cbc148"
            }
          ]
        }
      ]
    },
    {
      "name": "Cabwise",
      "item": [
        {
          "id": "d672e353-1854-4fe6-bff8-4e173b293c9b",
          "name": "Cabwise_Get",
          "request": {
            "url": "http://api.tfl.gov.uk/Cabwise/search?forceXml=%7B%7D&lat=%7B%7D&legacyFormat=%7B%7D&lon=%7B%7D&maxResults=%7B%7D&name=%7B%7D&optype=%7B%7D&radius=%7B%7D&twentyFourSevenOnly=%7B%7D&wc=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets taxis and minicabs contact information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "137874b7-2ca2-4595-a9ab-889f20450a0b"
            }
          ]
        }
      ]
    },
    {
      "name": "Journey",
      "item": [
        {
          "id": "70504c38-e906-454f-a5e9-8a20da796219",
          "name": "Journey_JourneyResults",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tfl.gov.uk",
              "path": [
                "Journey/JourneyResults/:from/to/:to"
              ],
              "query": [
                {
                  "key": "accessibilityPreference",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "adjustment",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "alternativeCycle",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "alternativeWalking",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "applyHtmlMarkup",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "bikeProficiency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "cyclePreference",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fromName",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "journeyPreference",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxTransferMinutes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxWalkingMinutes",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "nationalSearch",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "taxiOnlyTrip",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "time",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "timeIs",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "toName",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "useMultiModalCall",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "via",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "viaName",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "walkingOptimization",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "walkingSpeed",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "from",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "to",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Perform a journey planner search from the parameters specified in simple types."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cb771b5-cefa-4771-bf16-a37ffeabc0ec"
            }
          ]
        },
        {
          "id": "10b86fde-7dc9-4e9b-99c6-28b76d589b2c",
          "name": "Journey_Meta",
          "request": {
            "url": "http://api.tfl.gov.uk/Journey/Meta/Modes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all of the available journey planner modes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f7a8592-4f61-42a5-880e-f45ee6ddac5b"
            }
          ]
        }
      ]
    },
    {
      "name": "Line",
      "item": [
        {
          "id": "471c556e-8abd-440b-a654-45722a0c5779",
          "name": "Line_MetaDisruptionCategories",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Meta/DisruptionCategories",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid disruption categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a10b6325-1ed9-4c1e-840f-f2751c9d41af"
            }
          ]
        },
        {
          "id": "98807468-f6ba-4a8f-a987-edd7845b2c63",
          "name": "Line_MetaModes",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Meta/Modes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid modes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f38d502-d3f7-4514-a44a-6dfbae964ff8"
            }
          ]
        },
        {
          "id": "4c32f484-13a1-4443-8a54-0989aad6861c",
          "name": "Line_MetaServiceTypes",
          "request": {
            "url": "http://api.tfl.gov.uk/Line/Meta/ServiceTypes",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of valid servicetypes to filter on."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb216f58-d476-450e-8cb6-513694305215"
            }
          ]
        }
      ]
    }
  ]
}