---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Returns information on a person.
  description: BETA - By default the API will only return basic People information.
    Additional objects can be included by passing the object in the Includes parameter.
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Changes/People/History/:
    get:
      summary: Returns list of unique PersonId changes greater than or equal to date
        (UTC).
      description: Requires a valid Date.
      operationId: GetPersonChangeHistory
      x-api-path-slug: changespeoplehistory-get
      parameters:
      - in: query
        name: Date
        description: Starting date
      - in: query
        name: Skip
        description: Offset for paging
      - in: query
        name: Take
        description: Maximum number of rows returned
      responses:
        200:
          description: OK
      tags:
      - Changes
      - People
      - History
  /Changes/People/HistoryWithEntity/:
    get:
      summary: Returns list of unique PersonId and Entity changes greater than or
        equal to date (UTC).
      description: Requires a valid Date.
      operationId: GetPersonChangeHistoryWithEntity
      x-api-path-slug: changespeoplehistorywithentity-get
      parameters:
      - in: query
        name: Date
        description: Starting date
      - in: query
        name: Skip
        description: Offset for paging
      - in: query
        name: Take
        description: Maximum number of rows returned
      responses:
        200:
          description: OK
      tags:
      - Changes
      - People
      - HistoryWithEntity
  /Charts/People/Popular:
    get:
      summary: Returns list of popular celebrities based on IVA data.
      description: Requires Skip and Take. Maximum page size is 100.
      operationId: GetChartPeoplePopular
      x-api-path-slug: chartspeoplepopular-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - Charts
      - People
      - Popular
  /People/All:
    get:
      summary: Gets all People.
      description: Returns a AllPeopleResponse object containing a list of all poeple.
      operationId: GetAllPeople
      x-api-path-slug: peopleall-get
      parameters:
      - in: query
        name: Includes
        description: List of additional objects to include in the person response
      - in: query
        name: Skip
        description: Skips records using for paging results
      - in: query
        name: Take
        description: Limits the total items returned
      responses:
        200:
          description: OK
      tags:
      - People
  /People/RankedSearch/:
    get:
      summary: Find Person by Name ordered by rank.
      description: Find person using name ordered by rank.
      operationId: GetPersonRankedSearch
      x-api-path-slug: peoplerankedsearch-get
      parameters:
      - in: query
        name: StartsWith
      responses:
        200:
          description: OK
      tags:
      - People
      - RankedSearch
  /People/{Id}:
    get:
      summary: Returns information on a person.
      description: BETA - By default the API will only return basic People information.
        Additional objects can be included by passing the object in the Includes parameter.
      operationId: GetPerson
      x-api-path-slug: peopleid-get
      parameters:
      - in: path
        name: Id
        description: Required ID of Person
      - in: query
        name: Includes
        description: List of additional objects to include in the person response
      responses:
        200:
          description: OK
      tags:
      - People
      - Id
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