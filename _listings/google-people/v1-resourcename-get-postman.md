{
  "info": {
    "name": "Google People API Get Person",
    "_postman_id": "cd7ce68e-7bb4-4ac1-9f7d-0d18b3ca2b7e",
    "description": "Provides information about a person resource for a resource name. Use\n`people/me` to indicate the authenticated user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "people",
      "item": [
        {
          "id": "32c4e9f3-1762-44d1-839d-bb71218340be",
          "name": "people.people.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "people.googleapis.com",
              "path": [
                "v1/:resourceName"
              ],
              "query": [
                {
                  "key": "requestMask.includeField",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "resourceName",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information about a person resource for a resource name"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4e372d4-c091-4f86-8107-a74312383445"
            }
          ]
        }
      ]
    }
  ]
}