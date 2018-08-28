{
  "info": {
    "name": "My Space Post Activities Personid Self",
    "_postman_id": "d852b847-c690-423e-8e89-b8daf80b1495",
    "description": "Creates an activity for the user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "abd2d38c-96c6-4caf-b17e-2ae64d514374",
          "name": "1.0.activities.personId.selector.appId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/activities/:personId/:selector/:appId"
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
                  "key": "startIndex",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "updatedSince",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves activities created by an application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fe31946-3085-4924-b75a-a33400ee1e4f"
            }
          ]
        },
        {
          "id": "d6d8b923-4f40-4a25-bbba-86fb37d55f41",
          "name": "1.0.activities._supportedObjectTypes.get",
          "request": {
            "url": "http://api.myspace.com/1.0/activities/@supportedObjectTypes?count=%7B%7D&fields=%7B%7D&format=%7B%7D&startIndex=%7B%7D&updatedSince=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported object types."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1acd2d7-54a1-4f52-9f1a-48acd6eaa28b"
            }
          ]
        },
        {
          "id": "b12089f8-1d73-4ca9-aaef-52943b7dddb8",
          "name": "1.0.activities._supportedVerbs.get",
          "request": {
            "url": "http://api.myspace.com/1.0/activities/@supportedVerbs?count=%7B%7D&fields=%7B%7D&format=%7B%7D&startIndex=%7B%7D&updatedSince=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported verbs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88cad129-3d70-4e09-8883-752cc3343199"
            }
          ]
        },
        {
          "id": "6effe84f-623c-43c5-a9f6-d9bc11b698a3",
          "name": "1.0.activities._supportedFields.get",
          "request": {
            "url": "http://api.myspace.com/1.0/activities/@supportedFields?count=%7B%7D&fields=%7B%7D&format=%7B%7D&startIndex=%7B%7D&updatedSince=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported fields."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f59237dd-d78d-4b9a-9cc8-27404887b2d9"
            }
          ]
        },
        {
          "id": "6d3d0d1e-5d4b-4c4d-af98-bbbc450fe913",
          "name": "1.0.activities.personId._self.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/activities/:personId/@self"
              ],
              "query": [
                {
                  "key": "Content-Type",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an activity for the user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "060e3e4a-c8ab-454e-b8f4-ae5f50cb395b"
            }
          ]
        }
      ]
    }
  ]
}