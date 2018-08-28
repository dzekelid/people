{
  "info": {
    "name": "My Space Get Albums Personid Self",
    "_postman_id": "1ead40a1-e54d-42fa-92d4-809426e593b6",
    "description": "Retrieves the current user's albums.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Albums",
      "item": [
        {
          "id": "af66887a-4d2b-4272-a1b1-89091654b2fa",
          "name": "1.0.albums.personId._self.albumId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/albums/:personId/@self/:albumId"
              ],
              "variable": [
                {
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves an album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "319b6a7e-85e8-4fa5-8dd9-e3d3c2c5a22f"
            }
          ]
        },
        {
          "id": "b9f7ba5b-4fb5-4146-8145-77e91e0b86af",
          "name": "1.0.albums.personId._self.albumId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/albums/:personId/@self/:albumId"
              ],
              "variable": [
                {
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "Specifies Content Type",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Update an Album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "809b3005-9946-430c-a6ed-f488a7f38d60"
            }
          ]
        },
        {
          "id": "54e09eb3-1898-47bc-b338-1db0e6376bc4",
          "name": "1.0.albums.personId._self.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/albums/:personId/@self"
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
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "msPrivacyLevel",
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the current user's albums."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9b536c3-7e9e-4193-ad2b-14abb5370e0c"
            }
          ]
        },
        {
          "id": "d6857d63-9fb7-45e3-b072-21fe1e9bd100",
          "name": "1.0.albums.personId._self.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/albums/:personId/@self"
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "Specifies Content Type",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Adding an Album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "883bfcfd-a01a-4338-9d01-9d539708e4cb"
            }
          ]
        }
      ]
    }
  ]
}