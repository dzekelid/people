{
  "info": {
    "name": "My Space Get Opensearch People",
    "_postman_id": "9ef78d32-9276-499a-8466-e56a5af8973b",
    "description": "Returns search results for people.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Opensearch",
      "item": [
        {
          "id": "4dc4f09b-90ef-416e-af97-6bd016913159",
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
              "id": "bae9f542-b4e4-456c-8337-0d55e7af843a"
            }
          ]
        },
        {
          "id": "e4f42c51-884a-4073-a57d-d89fb4107c8e",
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
              "id": "b92f8910-064a-49ca-acc2-709cbaaa42fb"
            }
          ]
        },
        {
          "id": "0c97d01a-1bf0-4e75-a4cf-2122effebb26",
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
              "id": "727a725b-7e44-42e6-9d29-b1c9c72fbf41"
            }
          ]
        }
      ]
    }
  ]
}