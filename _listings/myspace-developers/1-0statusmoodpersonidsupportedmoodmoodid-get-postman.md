{
  "info": {
    "name": "My Space Get Statusmood Personid @supportedmood Moodid",
    "_postman_id": "e6dbe679-bd4b-431c-b588-f94dfe533f64",
    "description": "Retrieves a mood.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Statusmoodcomments",
      "item": [
        {
          "id": "5c403578-f3f2-4112-8f35-a34c97e802ab",
          "name": "1.0.statusmoodcomments.personId._self.statusId.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmoodcomments/:personId/@self/:statusId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
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
                  "key": "selector",
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
                  "id": "statusId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Posts a comment to a status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "786306dd-8dcf-4c13-8e3c-31c44ad02df8"
            }
          ]
        }
      ]
    },
    {
      "name": "Statusmood",
      "item": [
        {
          "id": "3360771a-977a-4541-b69e-87c698c17885",
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
              "id": "8a4231f6-cebd-41a3-bb3b-835fb1cdd0ce"
            }
          ]
        },
        {
          "id": "9c434a6b-4cc5-436a-8304-730981c85c74",
          "name": "1.0.statusmood.personId.selector.friendId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector/:friendId"
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
            "description": "Returns a status for Friend."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7de879b3-f212-4c4c-ac11-3e3ecfd9cf92"
            }
          ]
        },
        {
          "id": "084ddd92-2174-4e7f-9fe8-dc1976687f56",
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
              "id": "da881490-f714-4387-97b4-d9a91b9bd29e"
            }
          ]
        },
        {
          "id": "eabf1ae0-241a-4b56-9047-2d1549eb4d20",
          "name": "1.0.statusmood.personId.selector.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector"
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
            "description": "Returns a status for User."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "445f1e80-93e4-4cc5-88b8-a943902f786a"
            }
          ]
        },
        {
          "id": "689e0a81-6e13-4dc7-836a-e0353fb6ba93",
          "name": "1.0.statusmood.personId.selector.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/:selector"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
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
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a status for User."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47298812-c652-4cf8-9ea4-43efb5fe80af"
            }
          ]
        },
        {
          "id": "2889c1af-759a-400c-89bd-5c8eaf806b08",
          "name": "1.0.statusmood.personId._supportedMood.moodId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood/:moodId"
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
                  "id": "moodId",
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
            "description": "Retrieves a mood."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5520939f-191b-4989-905c-5f633b577ed0"
            }
          ]
        },
        {
          "id": "0f7edbdb-489e-4bad-b02a-13270fc25f05",
          "name": "1.0.statusmood.personId._supportedMood.moodId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood/:moodId"
              ],
              "query": [
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                },
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
                  "id": "moodId",
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
            "body": {
              "mode": "raw"
            },
            "description": "Updates a mood."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da7054d9-356a-434a-becb-e28bcd344950"
            }
          ]
        }
      ]
    }
  ]
}