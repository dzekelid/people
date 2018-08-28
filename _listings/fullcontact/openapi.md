swagger: "2.0"
x-collection-name: FullContact
x-complete: 1
info:
  title: FullContact Location API
  description: the-api-for-managing-fullcontact-locations
  termsOfService: https://www.fullcontact.com/terms/
  version: 1.0.0
host: api.fullcontact.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/person.json:
    get:
      summary: ""
      description: Find out more about a person
      operationId: -v2-person
      x-api-path-slug: v2person-json-get
      parameters:
      - in: query
        name: email
        description: The email address you wish to query
      responses:
        200:
          description: OK
      tags:
      - People