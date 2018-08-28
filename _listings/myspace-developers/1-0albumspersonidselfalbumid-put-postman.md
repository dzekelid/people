{
  "info": {
    "name": "My Space Put Albums Personid Self Albums",
    "_postman_id": "5bbfb20e-70f3-41d3-b383-f02fff7b93dd",
    "description": "Update an Album.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Albums",
      "item": [
        {
          "id": "efb834fc-8cb7-4da4-b584-40a98e9d72c3",
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
              "id": "3dc8d076-ec50-4857-8fbc-7711dc1e875d"
            }
          ]
        }
      ]
    }
  ]
}