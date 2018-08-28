{
  "info": {
    "name": "My Space Post Appdata Personid Selector Appid",
    "_postman_id": "eb28312c-55c7-43b6-b875-761af643c990",
    "description": "Adds or updates a specified user's application data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Appdata",
      "item": [
        {
          "id": "934e635d-608c-4465-91df-dbc10b9d49aa",
          "name": "1.0.appdata.personId.selector.appId.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/appdata/:personId/:selector/:appId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "appId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates a specified user's application data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21cadbc0-b90b-45ae-855e-47cfa40f1cf5"
            }
          ]
        },
        {
          "id": "d2c40525-c1d6-4381-bb1e-072b526f4fb6",
          "name": "1.0.appdata.personId.selector.appId.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/appdata/:personId/:selector/:appId"
              ],
              "query": [
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "appId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "selector",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified user's application data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3749ca81-3300-47d2-bd33-2f7cdb3c1fac"
            }
          ]
        }
      ]
    }
  ]
}