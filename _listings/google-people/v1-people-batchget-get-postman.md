{
  "info": {
    "name": "Google People API Get People",
    "_postman_id": "27978eea-3fff-49bd-911c-6ef6b3bfd32f",
    "description": "Provides information about a list of specific people by specifying a list\nof requested resource names. Use `people/me` to indicate the authenticated\nuser.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "people",
      "item": [
        {
          "id": "3367b1be-ffd7-4bb1-b1c6-e584a4aa419a",
          "name": "people.people.getBatchGet",
          "request": {
            "url": "http://people.googleapis.com/v1/people:batchGet?requestMask.includeField=%7B%7D&resourceNames=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information about a list of specific people by specifying a list\nof requested resource names"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df8ba065-f1ac-4089-ba65-81a6e2bdbdca"
            }
          ]
        }
      ]
    }
  ]
}