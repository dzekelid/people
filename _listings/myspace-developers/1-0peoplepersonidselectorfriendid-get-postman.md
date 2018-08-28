{
  "info": {
    "name": "My Space Get People Personid Selector Friendid",
    "_postman_id": "88db02f1-8650-405a-8d64-1d5a51ca609c",
    "description": "Retrieves friend data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Statusmoodcomments",
      "item": [
        {
          "id": "dbfad14f-38e8-4305-9961-ccb8b91d6f9a",
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
              "id": "51ac71b1-f1a1-4fa8-9c92-6971c42266ec"
            }
          ]
        }
      ]
    },
    {
      "name": "Statusmood",
      "item": [
        {
          "id": "17e17794-4c4b-4fce-989d-4abd720fd0c8",
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
              "id": "3438695a-1063-4716-b3e5-187b4831754e"
            }
          ]
        },
        {
          "id": "09fc9e6a-3a49-4d90-ac83-21681ce249ef",
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
              "id": "7c211191-7066-45da-9410-f3f709688ce3"
            }
          ]
        },
        {
          "id": "186215a1-a9cf-4031-87a6-0117bce49d97",
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
              "id": "033ba8a2-f14c-47de-b17d-8cbb3e92902e"
            }
          ]
        },
        {
          "id": "7e13176c-cc8d-4794-8bae-b2a9cddf58d7",
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
              "id": "fde99db8-0d9a-4c27-9eee-c96db0aea363"
            }
          ]
        },
        {
          "id": "343ed5f3-aaed-45fe-b8c2-64eda173992f",
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
              "id": "daff6487-0ce3-47f3-ab65-59ab89de390f"
            }
          ]
        },
        {
          "id": "2d6a1bcf-1fa4-4fd5-8838-596128df785d",
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
              "id": "1018c419-e17f-4081-9a3a-a127fb3988ab"
            }
          ]
        },
        {
          "id": "7b415430-4c47-4240-a167-88d0014cb4ad",
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
              "id": "cc6a5b1a-253b-49ac-bbe9-58f723b1f30f"
            }
          ]
        },
        {
          "id": "09413a5d-ab71-4a48-860f-34eea3d8f864",
          "name": "1.0.statusmood.personId._supportedMood.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all supported moods."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d6ea50c-255f-439f-a5ff-860b56804055"
            }
          ]
        },
        {
          "id": "3388331e-5703-48d3-98e1-92c405ba4652",
          "name": "1.0.statusmood.personId._supportedMood.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/statusmood/:personId/@supportedMood"
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
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a mood."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a535e3fc-d3ec-466b-8d92-6ce99d2b71b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Mediaitemcomments",
      "item": [
        {
          "id": "f56d36f9-6883-4ef5-be1e-373ec44539c1",
          "name": "1.0.mediaitemcomments.personId._self.albumId.mediaItemId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaitemcomments/:personId/@self/:albumId/:mediaItemId"
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
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaItemId",
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
            "description": "Retrieves item comments from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d69f7063-87e7-46db-bbf8-783421d8567e"
            }
          ]
        }
      ]
    },
    {
      "name": "MediaItems",
      "item": [
        {
          "id": "51701418-9469-4400-8236-35b9c29c9762",
          "name": "1.0.mediaItems.personId._videos._supportedcategories.categoryId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@videos/@supportedcategories/:categoryId"
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
                  "id": "categoryId",
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
            "description": "Retrieves videos for Category."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "518f4b0a-bef4-4a6e-bf8e-6140458cf1a1"
            }
          ]
        },
        {
          "id": "83ba5f3a-1200-4fd7-9c11-bfd159d1e06a",
          "name": "1.0.mediaItems.personId._videos._supportedcategories.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@videos/@supportedcategories"
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
            "description": "Retrieves supported categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ce0ff1a-96a2-4d44-b9f6-fe7b0d459d1f"
            }
          ]
        },
        {
          "id": "b7db126e-685a-4a71-ae29-9a7f6856720d",
          "name": "1.0.mediaItems.personId._self._videos.mediaItemId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos/:mediaItemId"
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
                  "id": "mediaItemId",
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
            "description": "Retrieves a video."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afd2ff0e-4896-4784-9f2c-8dc04e09075b"
            }
          ]
        },
        {
          "id": "f14c1996-a7dd-4422-b5bd-7dcf9c7edfea",
          "name": "1.0.mediaItems.personId._self._videos.mediaItemId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos/:mediaItemId"
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
                  "id": "mediaItemId",
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
            "description": "Updates an video."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72f74a56-9903-4808-ab9a-8cc37db49366"
            }
          ]
        },
        {
          "id": "8039a92c-db16-4191-a1b3-2cf6d8c6032f",
          "name": "1.0.mediaItems.personId._self._videos.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos"
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
            "description": "Retrieves all the videos."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4042c5ac-3e85-47c6-8af3-6ced5b7a8df1"
            }
          ]
        },
        {
          "id": "257af453-3215-407e-8171-5b017c01d770",
          "name": "1.0.mediaItems.personId._self._videos.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/@videos"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds videos from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b70f1dba-5bdc-4efe-b9e5-7c1b1dada259"
            }
          ]
        },
        {
          "id": "24814125-e889-4706-997c-ec1097f80b30",
          "name": "1.0.mediaItems.personId._self.albumId.mediaItemId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId/:mediaItemId"
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
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaItemId",
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
            "description": "Retrieves an item from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06983499-a861-413b-9a94-7c072bb66acc"
            }
          ]
        },
        {
          "id": "19fbb347-a9a1-4f8b-adbd-23d3fdc7cf2a",
          "name": "1.0.mediaItems.personId._self.albumId.mediaItemId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId/:mediaItemId"
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
                  "id": "albumId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaItemId",
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
            "description": "Updates an item from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ef367b8-ed50-4f06-b974-f624b07c195f"
            }
          ]
        },
        {
          "id": "421f66de-7d9b-44ba-9d7f-ce1287e60d18",
          "name": "1.0.mediaItems.personId._self.albumId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId"
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
            "description": "Retrieves items from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1ac9909-c87f-4e77-b669-ceb1961f913a"
            }
          ]
        },
        {
          "id": "bfaa4ac3-e168-4baf-9c9e-5c3252e8a945",
          "name": "1.0.mediaItems.personId._self.albumId.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/mediaItems/:personId/@self/:albumId"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds items from a specified album."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e71d883-95d8-48b9-8e30-f97154827155"
            }
          ]
        },
        {
          "id": "35698358-da9e-41eb-884e-4c18c0fda43d",
          "name": "1.0.mediaItems._supportedFields.get",
          "request": {
            "url": "http://api.myspace.com/1.0/mediaItems/@supportedFields?count=%7B%7D&fields=%7B%7D&format=%7B%7D&msPrivacyLevel=%7B%7D&startIndex=%7B%7D",
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
              "id": "1c0a3dae-a9f6-461b-81c1-fd7006c4b6d3"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "79494591-3025-4bfb-8f2c-f4cabdf05524",
          "name": "stream.subscription._all.get",
          "request": {
            "url": "http://api.myspace.com/stream/subscription/@all?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all subscriptions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8534ca4-ffd3-40ac-af6c-3aaa6d9e76c5"
            }
          ]
        },
        {
          "id": "d672b0f4-c782-4c14-9c85-ad499d672b4a",
          "name": "stream.subscription._all.delete",
          "request": {
            "url": "http://api.myspace.com/stream/subscription/@all?format=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes all subscriptions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6c0360b9-03af-4d9e-883e-bab337dfed42"
            }
          ]
        },
        {
          "id": "6739023f-74f8-40f1-9af4-04ddcbbc2446",
          "name": "stream.subscription.subscriptionId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "stream/subscription/:subscriptionId"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a subscription."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce34e5a3-dfaf-41f5-93f1-dced11ab84d1"
            }
          ]
        },
        {
          "id": "cc71f6d7-3ba1-4690-97ab-04b809208ccc",
          "name": "stream.subscription.subscriptionId.put",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "stream/subscription/:subscriptionId"
              ],
              "query": [
                {
                  "key": "Content-Type",
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
                  "id": "subscriptionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a subscription."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3973893a-e984-450e-8223-0f578beba613"
            }
          ]
        },
        {
          "id": "2f1e3ece-cdc3-4658-a258-20359df95015",
          "name": "stream.subscription.subscriptionId.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "stream/subscription/:subscriptionId"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a subscription."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab45ec9e-0a3f-4009-b1d0-7b2a9a76adbc"
            }
          ]
        },
        {
          "id": "c1088b63-ad16-47f0-8670-8a4357ec417b",
          "name": "stream.subscription.post",
          "request": {
            "url": "http://api.myspace.com/stream/subscription?Content-Type=%7B%7D&format=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a subscription."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7768eb4-8916-4490-a121-06d564b9a4a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Opensearch",
      "item": [
        {
          "id": "af61b232-6cc8-4e3b-a766-251751416418",
          "name": "opensearch.videos.get",
          "request": {
            "url": "http://api.myspace.com/opensearch/videos?count=%7B%7D&culture=%7B%7D&format=%7B%7D&searchTerms=%7B%7D&startPage=%7B%7D&tag=%7B%7D&videoMode=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns search results for videos."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e6cd380-712d-4295-af2a-f9e3eed43a2e"
            }
          ]
        },
        {
          "id": "b732dc27-177e-4712-ac7b-ba9d3d7a81af",
          "name": "opensearch.images.get",
          "request": {
            "url": "http://api.myspace.com/opensearch/images?count=%7B%7D&culture=%7B%7D&format=%7B%7D&searchTerms=%7B%7D&sortBy=%7B%7D&sortOrder=%7B%7D&startPage=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns search results for images."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f390dd2-6003-408d-a1e0-972e07c75e0d"
            }
          ]
        },
        {
          "id": "1ca3957c-425f-4fcd-8c8c-edb0ea413c52",
          "name": "opensearch.people.get",
          "request": {
            "url": "http://api.myspace.com/opensearch/people?count=%7B%7D&countryCode=%7B%7D&culture=%7B%7D&distance=%7B%7D&format=%7B%7D&gender=%7B%7D&hasPhoto=%7B%7D&latitude=%7B%7D&location=%7B%7D&longitude=%7B%7D&maxAge=%7B%7D&minAge=%7B%7D&searchBy=%7B%7D&searchTerms=%7B%7D&startPage=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns search results for people."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fed896eb-e6f4-44ca-8076-66b91fe8234a"
            }
          ]
        }
      ]
    },
    {
      "name": "Profilecomments",
      "item": [
        {
          "id": "9a5be6c2-a2d0-4646-bd13-f6aefb422064",
          "name": "1.0.profilecomments.personId._self.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/profilecomments/:personId/@self"
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
            "description": "Retrieves profile comments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84807413-a5f8-4cc0-af8c-f3a454a724b3"
            }
          ]
        }
      ]
    },
    {
      "name": "People",
      "item": [
        {
          "id": "ed132f63-8f1a-44bc-af2b-008a7e073d93",
          "name": "1.0.people.personId.selector.friendId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/people/:personId/:selector/:friendId"
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
            "description": "Retrieves friend data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13f91d0c-2f76-4282-a8d9-ddf791df1d2c"
            }
          ]
        }
      ]
    }
  ]
}