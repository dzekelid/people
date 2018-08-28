swagger: "2.0"
x-collection-name: Google People
x-complete: 1
info:
  title: Google People
  description: provides-access-to-information-about-profiles-and-contacts-
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
  /v1/{resourceName}:
    get:
      summary: Get Person
      description: |-
        Provides information about a person resource for a resource name. Use
        `people/me` to indicate the authenticated user.
      operationId: people.people.get
      x-api-path-slug: v1resourcename-get
      parameters:
      - in: query
        name: requestMask.includeField
        description: Comma-separated list of fields to be included in the response
      - in: path
        name: resourceName
        description: The resource name of the person to provide information about
      responses:
        200:
          description: OK
      tags:
      - People