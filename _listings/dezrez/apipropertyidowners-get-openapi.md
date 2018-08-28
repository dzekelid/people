---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez For a given property, will return owning PeopleGroup
  version: 1.0.0
  description: For a given property, will return owning peoplegroup.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/globalsearch/people:
    get:
      summary: Search for People across the system.
      description: Search for people across the system..
      operationId: GlobalSearch_PeopleBydataContract.termBydataContract.pageSizeBydataContract.pageNumberBydataContract
      x-api-path-slug: apiglobalsearchpeople-get
      parameters:
      - in: query
        name: dataContract.branchId
      - in: query
        name: dataContract.excludeArchived
      - in: query
        name: dataContract.excludeDeleted
      - in: query
        name: dataContract.groupTypes
      - in: query
        name: dataContract.lastUpdated
      - in: query
        name: dataContract.pageNumber
      - in: query
        name: dataContract.pageSize
      - in: query
        name: dataContract.serviceType
      - in: query
        name: dataContract.term
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - SearchPeople
      - Across
      - System
  /api/property/{id}/owners:
    get:
      summary: For a given property, will return owning PeopleGroup
      description: For a given property, will return owning peoplegroup.
      operationId: Property_OwnersByid
      x-api-path-slug: apipropertyidowners-get
      parameters:
      - in: path
        name: id
        description: property id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - For
      - Given
      - Property
      - ""
      - Will
      - Return
      - Owning
      - PeopleGroup
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