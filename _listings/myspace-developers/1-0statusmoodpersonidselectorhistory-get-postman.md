{
  "info": {
    "name": "My Space Get Statusmood Personid Selector History",
    "_postman_id": "f741f250-dd44-4d99-baad-acae8cdc4d6b",
    "description": "Returns History User.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Statusmood",
      "item": [
        {
          "id": "66e2d2da-38c9-456b-8ab7-1590c9d22ace",
          "name": "1.0.statusmood.personId.selector.friendId.history.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector/:friendId/history"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "friendId",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns History Friend."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8702305f-de44-45cb-a845-4796793dc744"
            }
          ]
        },
        {
          "id": "38d93214-22f9-42c3-aa47-26dca08a99ab",
          "name": "1.0.statusmood.personId.selector.history.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector/history"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterOp",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filterValue",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns History User."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f485e58c-149e-4a4b-ad49-03c83ef21262"
            }
          ]
        }
      ]
    }
  ]
}