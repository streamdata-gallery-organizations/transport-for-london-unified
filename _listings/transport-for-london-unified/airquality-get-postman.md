{
  "info": {
    "name": "Transport for London Unified Air Quality",
    "_postman_id": "8f64ea9c-6804-4138-96b3-c54846cca745",
    "description": "Gets air quality data feed.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accent",
      "item": [
        {
          "id": "7ffa7c26-aa72-4c76-9641-2fc6b5a7d9ff",
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
              "id": "92e88354-4894-4c0e-8223-b53b7b11fd28"
            }
          ]
        }
      ]
    },
    {
      "name": "Air",
      "item": [
        {
          "id": "739b69b4-c272-48b9-b210-4186d9619b5e",
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
              "id": "a42d649e-3eb6-4a13-a5fe-f34914cb1034"
            }
          ]
        }
      ]
    }
  ]
}