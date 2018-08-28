---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr People Get Info
  description: Get information about a user.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.people.findByEmail:
    get:
      summary: People Find By Email
      description: Return a user's NSID, given their email address
      operationId: getRestMethodFlickr.people.findbyemail
      x-api-path-slug: restmethodflickr-people-findbyemail-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: find_email
        description: The email address of the user to find (may be primary or secondary)
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - People
      - FindByEmail
  /rest/?method=flickr.people.findByUsername:
    get:
      summary: People Find By Username
      description: Return a user's NSID, given their username.
      operationId: getRestMethodFlickr.people.findbyusername
      x-api-path-slug: restmethodflickr-people-findbyusername-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: username
        description: The username of the user to lookup
      responses:
        200:
          description: OK
      tags:
      - People
      - FindByUsername
  /rest/?method=flickr.people.getInfo:
    get:
      summary: People Get Info
      description: Get information about a user.
      operationId: getRestMethodFlickr.people.getinfo
      x-api-path-slug: restmethodflickr-people-getinfo-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: user_id
        description: The NSID of the user to fetch information about
      responses:
        200:
          description: OK
      tags:
      - People
      - GetInfo
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---