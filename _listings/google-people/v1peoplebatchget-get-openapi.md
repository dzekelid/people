---
swagger: "2.0"
x-collection-name: Google People
x-complete: 0
info:
  title: Google People API Get People
  description: |-
    Provides information about a list of specific people by specifying a list
    of requested resource names. Use `people/me` to indicate the authenticated
    user.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: people.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/people:batchGet:
    get:
      summary: Get People
      description: |-
        Provides information about a list of specific people by specifying a list
        of requested resource names. Use `people/me` to indicate the authenticated
        user.
      operationId: people.people.getBatchGet
      x-api-path-slug: v1peoplebatchget-get
      parameters:
      - in: query
        name: requestMask.includeField
        description: Comma-separated list of fields to be included in the response
      - in: query
        name: resourceNames
        description: The resource name, such as one returned by[`people
      responses:
        200:
          description: OK
      tags:
      - People
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