{
  "info": {
    "name": "Flickr Get People Photos",
    "_postman_id": "bec8617f-8fbd-4cd8-98ad-e55876e7653f",
    "description": "Return photos from the given user's photostream",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "photos",
      "item": [
        {
          "id": "ef9da2a8-a551-4d62-b63a-ffedfccf285c",
          "name": "getMediaByPersonID",
          "request": {
            "url": "http://api.flickr.com/services/rest?method=flickr.people.getPhotos?api_key=%7B%7D&content_type=%7B%7D&max_taken_date=%7B%7D&max_upload_date=%7B%7D&min_taken_date=%7B%7D&min_upload_date=%7B%7D&page=%7B%7D&per_page=%7B%7D&privacy_filter=%7B%7D&safe_search=%7B%7D&user_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return photos from the given user's photostream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f59d8eb5-c8fd-4db5-96c5-a18127eedb57"
            }
          ]
        }
      ]
    }
  ]
}