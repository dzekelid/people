{
  "info": {
    "name": "Clearbit Person Retrieves a person and company by email address",
    "_postman_id": "2d115664-53d0-4ac6-bbe6-08590dc1ff97",
    "description": "Retrieves a person and company by email address.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "people",
      "item": [
        {
          "id": "fc4b0747-72a8-4fc3-8abb-453f50ef7ca9",
          "name": "getCombined",
          "request": {
            "url": "http://person.clearbit.com/v2/combined/find?email=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a person and company by email address"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06e5d7bf-5556-4407-8489-7d6200bf369b"
            }
          ]
        }
      ]
    }
  ]
}