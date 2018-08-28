{
  "info": {
    "name": "Flickr Get People",
    "_postman_id": "d590a5f6-8d0e-477f-97a2-e8df9846e7a7",
    "description": "Returns a person",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "photos",
      "item": [
        {
          "id": "ec22bc10-c204-4ba5-9bb9-88e6c65b23f4",
          "name": "getPersonByID",
          "request": {
            "url": "http://api.flickr.com/services/rest?method=flickr.people.getInfo?api_key=%7B%7D&user_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a person"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dec34f3e-b287-4278-9e2e-ef2516f0b5b4"
            }
          ]
        }
      ]
    }
  ]
}