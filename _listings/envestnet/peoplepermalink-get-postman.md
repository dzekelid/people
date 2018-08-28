{
  "info": {
    "name": "Crunch Base Get People",
    "_postman_id": "83edd8f3-4c6c-4edb-bc62-ac1593e8503c",
    "description": "Get People Using Permalink",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Acquisitions",
      "item": [
        {
          "id": "854e9289-1536-42fe-96e5-dd7a451043f2",
          "name": "acquistions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "acquisitions/:uuid"
              ],
              "query": [
                {
                  "key": "user_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pull from Acquisition"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2624e4fb-1ced-4a4c-bd7b-e3e4fb5fee7a"
            }
          ]
        },
        {
          "id": "50ac3335-7cfc-46c5-a053-a8dfbe7d46cb",
          "name": "acquisitionsRelationships",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "acquisitions/:uuid/:relationship_name"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_order",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "relationship_name",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Acquisitions Relationships"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef097ae0-fc14-4399-91f0-2cedf392f9a3"
            }
          ]
        }
      ]
    },
    {
      "name": "Categories",
      "item": [
        {
          "id": "e01a3185-6d99-492f-a274-20b7a370abb6",
          "name": "categories",
          "request": {
            "url": "http://api.crunchbase.com/v/3/categories?page=%7B%7D&sort_order=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc6c1bd9-9efa-4234-9864-cda3a0660e61"
            }
          ]
        }
      ]
    },
    {
      "name": "Funding",
      "item": [
        {
          "id": "4c3b1991-65a8-4961-b2ac-f3478f7e65ec",
          "name": "fundingRounds",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "funding-rounds/:uuid"
              ],
              "query": [
                {
                  "key": "user_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets funding rounds by UUID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "474c647f-eabb-45c1-9930-3c83cb5c726c"
            }
          ]
        },
        {
          "id": "05073e57-e1e7-47a6-9071-3bd7edfbd1d2",
          "name": "fundingRoundRelationships",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "funding-rounds/:uuid/:relationship_name"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_order",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "relationship_name",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Funding Rounds Relationships"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ce0caf9-c4a6-4187-b81a-095605961664"
            }
          ]
        }
      ]
    },
    {
      "name": "Funds",
      "item": [
        {
          "id": "2ed95b30-3775-4ccc-a9d7-78c798914de8",
          "name": "fundRelationships",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "funds/:uuid/:relationship_name"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_order",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "uuid",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "relationship_name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Fund Relationships"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "377f7836-d770-4931-b442-cd5883769a05"
            }
          ]
        },
        {
          "id": "b06e6dc3-952d-4b8c-897b-e20eea6579f9",
          "name": "funds",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "funds/:uuid"
              ],
              "variable": [
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Funds"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8db1071e-1794-434a-bb8a-d0b395c1ed18"
            }
          ]
        }
      ]
    },
    {
      "name": "Ipos",
      "item": [
        {
          "id": "65df2974-3db6-46b1-ae5f-05f2425f15cb",
          "name": "ipo",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "ipos/:uuid"
              ],
              "query": [
                {
                  "key": "user_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get IPO Using UUID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a66aa5e-64dd-47e6-8946-01fef9bbe7ec"
            }
          ]
        },
        {
          "id": "4cca472e-3e3d-41b7-9786-788dfc9fcb55",
          "name": "ipoRelationships",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "ipos/:uuid/:relationship_name"
              ],
              "query": [
                {
                  "key": "order",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "The page number to retrieve",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "relationship_name",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get IPO Relationships"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8767757a-d2a9-4ccf-bec7-9adc4105b2bf"
            }
          ]
        }
      ]
    },
    {
      "name": "Locations",
      "item": [
        {
          "id": "ffdcd468-8cc4-4c44-a747-51d07b36d789",
          "name": "locations",
          "request": {
            "url": "http://api.crunchbase.com/v/3/locations?page=%7B%7D&sort_order=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Locations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "464ddef3-9883-4578-82e2-fae524246bc6"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "77945540-d9bd-4c83-8f2f-894f020ecc34",
          "name": "organizations",
          "request": {
            "url": "http://api.crunchbase.com/v/3/organizations?categories=%7B%7D&category_uuids=%7B%7D&domain_name=%7B%7D&locations=%7B%7D&name=%7B%7D&organization_types=%7B%7D&page=%7B%7D&query=%7B%7D&sort_order=%7B%7D&updated_since=%7B%7D&user_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Organizations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc3b68ae-1f10-425c-89c3-b19d93a79991"
            }
          ]
        },
        {
          "id": "d66e693d-3855-45d7-acdf-35d9d4fff542",
          "name": "organizations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "organizations/:permalink"
              ],
              "query": [
                {
                  "key": "user_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "permalink",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Organization Using Permalink"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c1c1d91-0884-4ba1-a0c1-8f74d83e22b2"
            }
          ]
        },
        {
          "id": "80a12565-75d9-4747-890a-60645d112c7c",
          "name": "organizationRelationships",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "organizations/:permalink/:relationship_name"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_order",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "user_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "permalink",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "relationship_name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Organizations Relationships Using Permlink"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee8926e7-6133-43f7-86ee-4f1d88ae5712"
            }
          ]
        }
      ]
    },
    {
      "name": "People",
      "item": [
        {
          "id": "0754907a-a9b2-424e-8488-1ef34f279990",
          "name": "people",
          "request": {
            "url": "http://api.crunchbase.com/v/3/people?locations=%7B%7D&name=%7B%7D&page=%7B%7D&query=%7B%7D&socials=%7B%7D&sort_order=%7B%7D&types=%7B%7D&updated_since=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get People"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a624a13-ae64-492a-8927-c8f5858caa72"
            }
          ]
        },
        {
          "id": "42e5ff14-ba9d-48cf-93ca-e1b07f7a536a",
          "name": "people",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.crunchbase.com",
              "path": [
                "v",
                "3",
                "people/:permalink"
              ],
              "query": [
                {
                  "key": "user_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "permalink",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get People Using Permalink"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16cf9fde-ec4a-4b53-ae93-26fd8eb04a2a"
            }
          ]
        }
      ]
    }
  ]
}