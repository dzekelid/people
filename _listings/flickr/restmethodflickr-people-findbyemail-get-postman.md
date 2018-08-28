{
  "info": {
    "name": "Flickr People Find By Email",
    "_postman_id": "43333acf-ea4f-41e8-8b42-337a3a4a5f68",
    "description": "Return a user's NSID, given their email address",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "People",
      "item": [
        {
          "id": "b829e2b4-64f5-46b5-9932-25872009b93c",
          "name": "getRestMethodFlickr.people.findbyemail",
          "request": {
            "url": "http://api.flickr.com/services/rest/?method=flickr.people.findByEmail?api_key=%7B%7D&find_email=%7B%7D&format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return a user's NSID, given their email address"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65c02032-4fe2-45f6-90d1-f7564239e7a1"
            }
          ]
        }
      ]
    }
  ]
}