---
swagger: "2.0"
x-collection-name: TVmaze
x-complete: 0
info:
  title: TVmaze user Delete User Follows People Person
  description: Delete user follows people person.
  version: "1.0"
host: api.tvmaze.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/follows/people:
    get:
      summary: Get User Follows People
      description: Get user follows people.
      operationId: getUserFollowsPeople
      x-api-path-slug: userfollowspeople-get
      parameters:
      - in: query
        name: embed
        description: Embed full person info
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Follows
      - People
  /user/follows/people/{person_id}:
    delete:
      summary: Delete User Follows People Person
      description: Delete user follows people person.
      operationId: deleteUserFollowsPeoplePerson
      x-api-path-slug: userfollowspeopleperson-id-delete
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Follows
      - People
      - Person
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