{
  "info": {
    "name": "Crunch Base Get People",
    "_postman_id": "5d48165f-292b-4c7d-8a3a-5f188e0906eb",
    "description": "Get People",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Acquisitions",
      "item": [
        {
          "id": "23dde08f-b4ac-4ace-b5a8-58e2505c7eaf",
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
              "id": "90170a1e-6f8c-4d47-8d72-b6b7a3afbe40"
            }
          ]
        },
        {
          "id": "db20daa2-8d20-4f5e-81c8-235641cc64a4",
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
              "id": "8f7338fa-761e-484f-b496-ab1fbbfcd0d5"
            }
          ]
        }
      ]
    },
    {
      "name": "Categories",
      "item": [
        {
          "id": "a6fb7e70-1645-4525-a833-83540b3aa8e0",
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
              "id": "38bd1ed8-1703-447b-bdd8-9605ad51c876"
            }
          ]
        }
      ]
    },
    {
      "name": "Funding",
      "item": [
        {
          "id": "53591235-441a-466c-ac95-dc0cb08c0f9d",
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
              "id": "2d4cbd91-50e1-42e0-b4ab-314bf4b721a0"
            }
          ]
        },
        {
          "id": "c755c4ac-2489-4192-993a-466ad76e98a7",
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
              "id": "af9022e3-3134-482a-82fe-11cfd93d47dd"
            }
          ]
        }
      ]
    },
    {
      "name": "Funds",
      "item": [
        {
          "id": "9ce28315-d8a9-488b-9d85-06f73a9439ea",
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
              "id": "074371c1-7704-4bf2-a6bb-81609eccdcd2"
            }
          ]
        },
        {
          "id": "8ec6a5d4-10a6-44b8-b7f6-60bc6860bc63",
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
              "id": "311bdc55-8c5a-44db-9aa1-5629e051d7b5"
            }
          ]
        }
      ]
    },
    {
      "name": "Ipos",
      "item": [
        {
          "id": "72ed3097-71a9-4a61-a369-9621e3f8bc01",
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
              "id": "1cbae442-4d63-4ece-977f-aa897bcae8c6"
            }
          ]
        },
        {
          "id": "3b6f3bfe-a4cf-4421-b125-3634af536b51",
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
              "id": "6c5374f0-d09a-426c-8390-c2261ac83531"
            }
          ]
        }
      ]
    },
    {
      "name": "Locations",
      "item": [
        {
          "id": "1ac2b8d5-be30-4f1b-a2f7-e8a29133dce4",
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
              "id": "7288c5b9-b502-402e-979f-01f5cc4bcb03"
            }
          ]
        }
      ]
    },
    {
      "name": "Organizations",
      "item": [
        {
          "id": "0f45b604-0491-4ffb-b709-bec3c9af6b83",
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
              "id": "53d965bd-a3c6-4222-adac-a046de44da99"
            }
          ]
        },
        {
          "id": "60546652-8f44-457e-aa58-1e0f1847c095",
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
              "id": "4e50b283-fef5-4ca9-b00e-558aba92236c"
            }
          ]
        },
        {
          "id": "6a4ae7bf-e59d-4224-98cb-90d99290f2cd",
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
              "id": "a3b54c44-c8f5-4f25-8bed-f8ec85fbd8c0"
            }
          ]
        }
      ]
    },
    {
      "name": "People",
      "item": [
        {
          "id": "c85d8e00-1c9a-4a29-b5ed-da7911138493",
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
              "id": "58fcccb5-6b1c-43a6-823e-bcc75feb3e1e"
            }
          ]
        }
      ]
    }
  ]
}