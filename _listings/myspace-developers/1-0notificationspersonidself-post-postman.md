{
  "info": {
    "name": "My Space Post Notifications Personid Self",
    "_postman_id": "80561da6-27a3-4f88-a43a-50efa5910fb1",
    "description": "Sends notification.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Notifications",
      "item": [
        {
          "id": "74500865-2f5b-4307-8860-6c5f717bd38a",
          "name": "1.0.notifications.personId._self.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.myspace.com",
              "path": [
                "1.0/notifications/:personId/@self"
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
            "description": "Sends notification."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "339df2ab-45ca-484c-8ac9-9172fe05ae52"
            }
          ]
        }
      ]
    }
  ]
}