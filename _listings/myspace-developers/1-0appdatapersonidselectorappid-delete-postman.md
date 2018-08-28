{
  "info": {
    "name": "My Space Delete Appdata Personid Selector Appid",
    "_postman_id": "de7d7d34-1441-41e7-94f9-c3526e4fa217",
    "description": "Deletes a specified user's application data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Appdata",
      "item": [
        {
          "id": "e41716c8-e044-4e01-97a7-2a13cb32e4f3",
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
              "id": "bf18b0c2-3477-424f-b232-d96816e0054a"
            }
          ]
        }
      ]
    }
  ]
}