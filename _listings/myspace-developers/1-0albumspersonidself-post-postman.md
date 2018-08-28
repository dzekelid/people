{
  "info": {
    "name": "My Space Post Albums Personid Self",
    "_postman_id": "d40df62b-f6c9-42e9-b363-a13b72253f30",
    "description": "Adding an Album.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Albums",
      "item": [
        {
          "id": "24f493c9-adc6-4da8-872c-0d9e0430e116",
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
              "id": "80ae4ab7-1920-4eec-b088-ea5fd0f62007"
            }
          ]
        },
        {
          "id": "722dd435-eb33-4f96-9328-ca0072fd0cd2",
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
              "id": "e982a9c7-ecb2-4c9d-b8ec-319513aa1054"
            }
          ]
        },
        {
          "id": "b6796185-793a-4e00-a319-0646ffa7d8cb",
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
              "id": "86964856-882f-46dd-84e4-338f87073986"
            }
          ]
        }
      ]
    }
  ]
}