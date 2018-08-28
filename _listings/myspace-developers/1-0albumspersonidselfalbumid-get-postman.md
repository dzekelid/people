{
  "info": {
    "name": "My Space Get Albums Personid Self Albums",
    "_postman_id": "fa805890-5af2-475e-988f-80c57555421d",
    "description": "Retrieves an album.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Albums",
      "item": [
        {
          "id": "4c7686f9-cc17-46b4-a6ec-7f4efc2bfe9d",
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
              "id": "54f09e61-4b40-4b38-bdc7-bf17816a52f7"
            }
          ]
        },
        {
          "id": "ff82b919-4e10-4180-b174-111954c635ab",
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
              "id": "96f8de42-914b-4668-8a1e-fcdc778e63cf"
            }
          ]
        }
      ]
    }
  ]
}